# Desktop_API_URLpop

> *Update July 21, 2020:*   
>
>Chrome 84 users must disable deprecation TLS 1.0/1.1 for the Desktop API to function with WebSockets. 
>
>Please open [about://flags](about://flags) in the address bar and change “Enforce deprecation of legacy TLS versions” to **Disabled**:
> 
> A pending client update of Bria 5, Bria 6, and Bria Enterprise will correct
> this issue by enabling TLS 1.2 for the Desktop API.
---

A very basic HTML/JavaScript sample that listens for Bria Desktop API events and when a call is answered it does a Google search for the remote party number.

This example can easily be modified to do a lookup against any source, such as a contacts database or a CRM.




