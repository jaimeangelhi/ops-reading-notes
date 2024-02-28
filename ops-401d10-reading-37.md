# Reading 37

1. What are the three common stages of the Penetration Testing process and what tasks are performed at each one?

"Explore – The tester attempts to learn about the system being tested. This includes trying to determine what software is in use, what endpoints exist, what patches are installed, etc. It also includes searching the site for hidden content, known vulnerabilities, and other indications of weakness.
Attack – The tester attempts to exploit the known or suspected vulnerabilities to prove they exist.
Report – The tester reports back the results of their testing, including the vulnerabilities, how they exploited them and how difficult the exploits were, and the severity of the exploitation."


2. Explain a “main-in-the-middle proxy” in non-technical terms.

A man-in-the-middle proxy is like a teacher/qc agent that checks to make sure that the messages/packets/etc are going to be transferred correctly between the two.
"It stands between the tester’s browser and the web application so that it can intercept and inspect messages sent between browser and web application, modify the contents if needed, and then forward those packets on to the destination. It can be used as a stand-alone application, and as a daemon process."

3. What are the 2 spiders available for use in ZAP?

The two spiders available for use in ZAP are the traditional spider and the AJAX spider: "The traditional ZAP spider which discovers links by examining the HTML in responses from the web application. This spider is fast, but it is not always effective when exploring an AJAX web application that generates links using JavaScript.

For AJAX applications, ZAP’s AJAX spider is likely to be more effective. This spider explores the web application by invoking browsers which then follow the links that have been generated. The AJAX spider is slower than the traditional spider and requires additional configuration for use in a “headless” environment."
https://www.zaproxy.org/getting-started/

## Things I want to know more about

Deeper diving on ZAP and other MITM proxies.
