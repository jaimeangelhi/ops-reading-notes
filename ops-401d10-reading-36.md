# Reading 36

1. Explain how a cross-site scripting attack works in non-technical terms.

It's almost like laying a booby-trap in an unsuspecting location that then forces the victim to give up some area of security or protection that is then used against them (and the attacker takes advantage of and uses).
"Cross-site scripting works by manipulating a vulnerable web site so that it returns malicious JavaScript to users. When the malicious code executes inside a victim's browser, the attacker can fully compromise their interaction with the application."

2. What are the three types of XSS attacks?

Three types of XSS attacks are reflected XSS, stored XSS, and DOM-based XSS.
"Reflected XSS, where the malicious script comes from the current HTTP request.
Stored XSS, where the malicious script comes from the website's database.
DOM-based XSS, where the vulnerability exists in client-side code rather than server-side code."

3. If an attacker successfully exploits a XSS vulnerability, what malicious actions would they be able to perform?

The malicious actions they would be able to perform are impersonating or acting as the victim, accessing and manipulating their data, and additionally they can affect and alter the website itself.

"Impersonate or masquerade as the victim user.
Carry out any action that the user is able to perform.
Read any data that the user is able to access.
Capture the user's login credentials.
Perform virtual defacement of the web site.
Inject trojan functionality into the web site."


4. What are some security controls that can be implemented to prevent XSS attacks?

Security controls that can be implemented to prevent XSS attacks include using a burp suite web vulnerability scanner, enabling a good content security policy, and more: 
"-Filter input on arrival. At the point where user input is received, filter as strictly as possible based on what is expected or valid input.
-Encode data on output. At the point where user-controllable data is output in HTTP responses, encode the output to prevent it from being interpreted as active content. Depending on the output context, this might require applying combinations of HTML, URL, JavaScript, and CSS encoding.
-Use appropriate response headers. To prevent XSS in HTTP responses that aren't intended to contain any HTML or JavaScript, you can use the Content-Type and X-Content-Type-Options headers to ensure that browsers interpret the responses in the way you intend.
-Content Security Policy. As a last line of defense, you can use Content Security Policy (CSP) to reduce the severity of any XSS vulnerabilities that still occur."
(https://portswigger.net/web-security/cross-site-scripting)https://portswigger.net/web-security/cross-site-scripting

## Things I want to know more about

How often should I be checking my own sites for xss attacks?
