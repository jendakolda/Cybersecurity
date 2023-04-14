## Web application:
A web application is like a “program” that we can use without installation as long as we have a modern standard web browser, such as Firefox, Safari, or Chrome. Consequently, instead of installing every program you need, you only need to browse the related page. The following are some examples of web applications:

-   Webmail such as Tutanota, Protonmail, Outlook, and Gmail
-   Online office suites such as Microsoft Office 365 (Word, Excel, and PowerPoint), Google Drive (Docs, Sheets, and Slides), and Zoho Office (Writer, Sheet, and Show)
-   Online shopping such as Amazon.com, AliExpress, and Etsy

#### Issues:
1) Identification and Authentication Failure
2) Broken Access Control
	-   Failing to apply _the principle of the least privilege_ and giving users more access permissions than they need. For example, an online customer should be able to view the prices of the items, but they should not be able to change them.
	-   Being able to view or modify someone else’s account by using its unique identifier. For example, you don’t want one bank client to be able to view the transactions of another client.
	-   Being able to browse pages that require authentication (logging in) as an unauthenticated user. For example, we cannot let anyone view the webmail before logging in.
3) Injection
	An injection attack refers to a vulnerability in the web application where the user can insert malicious code as part of their input. One cause of this vulnerability is the lack of proper validation and sanitization of the user’s input.
4) Cryptographic Failures
	- Sending sensitive data in clear text
	- Relying on a weak cryptographic algorithm
	- Using default or weak keys for cryptographic functions