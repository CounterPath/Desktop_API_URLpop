# Desktop_API_URLpop
> *Update July 24, 2020:*   
>
> Bria 6.1.2 has been released to resolve issues with Chrome 84.  
> Bria 5 is a legacy edition and the next release for that older code stream will be in late September.  
> Bria 5 users can use the workaround below for now, use an alternative browser or they can purchase an upgrade to Bria 6 on Solo, Teams or Enterprise.  Contact desktopapi@counterpath.com for more info about the upgrade program if you to wish try Bria 6. This Github is not intended for selling so please contact us directly.
>
> Chrome 84 users must disable deprecation TLS 1.0/1.1 for the Desktop API to function with WebSockets. 
>
> Please open [about://flags](about://flags) in the address bar and change “Enforce deprecation of legacy TLS versions” to **Disabled**:
> 


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




