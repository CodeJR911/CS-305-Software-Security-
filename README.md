# CS-305-Software-Security-
SNHU
Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a financial services organization that delivers financial planning solutions and insurance solutions to meet their client’s needs. The issue presented to be addressed revolved around secure storage of private data along with secure communications to upload, and download given data.

•	What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
Implementation of the keystore.jks worked well in identifying vulnerabilities. Instructions were not always clear in many cases, but I managed to get the keystore operating in the terminal. Secure coding is extremely important because of the many threats. Data is constantly being breached. There are even some organizations looking to steal other organizations data. Secure code mitigates unknown threats. The overall wellbeing of an organization is greatly improved with secure software by increasing trustworthiness in the organization, it increases a organizations reliability, and it decreases the chances of a wide spread data leak for a given organization. 

•	What about the process of working through the vulnerability assessment did you find challenging or helpful?
Implementation of the hash algorithm presented challenges. The prime reason was due to the source code needing to create a class that threw an exception for the message digest to work. The examples provided did not show the same outcome, so implementing that was challenging. Getting the SSL to work was also a challenging task. Including my keystore file helped in resolving.

•	How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
Running the dependency checks was the first step in identifying security risks. Then came analyzing the source code to make sure no errors were present. Then, implementation of the TLS and the encryption. This route would be ideal in a real-world scenario. Finding a more accurate list of false positives on the dependency checks would be beneficial for readability and execution.

•	How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
For functionality, I ensured first that I had no code errors were present after running the application in my IDE. Once error-free code was established, running the service and opened the localhost to confirm that the output was correct, although I could not get the local host to connect. Verifying that the site was accessed via https using the self-signed certificate also presented challenges. After refactoring, check to see about new vulnerabilities by running another dependency check and cross-checking the results against the original run.

•	What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
The SSL certificates were very beneficial to the overall project. Utilizing them will be beneficial to test secure communications while developing websites. The dependency check tool was also a real asset. 

•	Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
Both projects present my current skill set in identifying and combating security threats. Although I will need further time and development to narrow the gaps in my work, now have a foundation to build upon for future employers.
