# CS305-Software-Security
<b>•	Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?</b>

Artemis Financial is a financial consulting company that creates personalized savings, retirements, investment, and insurance plans for their clients. They asked for their web-based application to be analyzed for security vulnerabilities and for the system to be modernized with secure file verification for secure communications. 

<b>•	What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?</b>

I manually reviewed the code and performed static testing by running a dependency check. False positives were suppressed, the application was updated to require a security certificate and then a secure SHA-256 hash algorithm was implemented for file verification. It is always important to code securely to protect client’s data from being breached. Financial institutions like Artemis Financial are the top targets for hackers due to how much sensitive data they transfer back and forth with their clients. Making sure their security is up to date makes the client feel safe utilizing the companies’ services. 

<b>•	What about the process of working through the vulnerability assessment did you find challenging or helpful?</b>

The most challenging part about running vulnerability assessment was filtering through the CVE’s. The list of security vulnerabilities was extensive and it was extremely time consuming to look each one up and find the solutions. The process was not necessarily difficult but rather very tedious.  

<b>•	How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?</b>

After doing a manual review utilizing the Vulnerability Assessment Process Flow Diagram and running a dependency check, I researched solutions to the vulnerabilities to determine my mitigation plan. Plugins needed to be updated, input verification needed to be implemented, and the HTTP protocol need to be switched to a HTTPS protocol. 

<b>•	How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?</b>

To ensure that the code a software application was functional and secure I researched the industry standard and top algorithms for secure file verifications. I chose to implement the SHA-256 hash algorithms which is the recommended choice by the National Institute of Standards and Technology. After refactoring the code, I ran a second dependency check and compared it with the original to make sure there were no new vulnerabilities introduced into the system and tested it the hash function with a self-signed certificate. 

<b>•	What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?</b>
  
  Utilizing OWSAP’s dependency check plugin made it easy and free way to find vulnerabilities so I would recommend it and utilize in in the future. The Vulnerability Process Flow Diagram was also a useful tool to use as a reference and guided me through the manual review.  
  
  <b>•	Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?</b>
  
   For the project we have been asked to submit, I feel that it showcases several important capabilities including running vulnerability reports, updating a system to a HTTPS protocol, and my ability to write a secure hash-algorithm.  
