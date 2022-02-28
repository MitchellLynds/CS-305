# CS-305
Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

The client was a financial firm hiring Global Rain to build a new software application. As a financial firm it was important that the application be secure. The specific issue I worked to address was generation and verification of authentication certificates and overall security of the application.

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

The data conversion or MessageDigest requires try/catch error handling. It is important not to reveal details in exception outputs such as the string that caused the error. Coding securely is important because the ramifications of security breaches can be extreme, including financial and legal repercussions. Software security serves to shield a company from those risks as much as possible.

What about the process of working through the vulnerability assessment did you find challenging or helpful?
How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

The most challenging part of the vulnerability assessment was the learning curve for understanding the structure of web applications. In order to increase layers of security we would work our way through the vulnerability assessment flow chart. I used and would use in the future the NIST National Vulnerability Database for identifying and addressing vulnerabilities. 

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?

In order to ensure the code was functional we created "Self-signed" certificates so that we could test run the application locally. After refactoring the code we ran another dependency check to see if any of the libraries added introduced a new known vulnerability and then reexamined the code functionality to make sure it was implemented in a secure way. I will continue to use Maven on any web application projects in order to quickly identify potential vulnerabilities. 

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

I think this assignment showcases an understanding of the mechanisms behind secure web applications such as certificates, encryption and REST API.
