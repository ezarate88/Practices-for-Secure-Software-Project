# Practices-for-Secure-Software-Project
Report Written for SNHU Course CS-305 Software Security

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial is a financial institutions that builds and develops financial plans for it's clientele. For their webpage, they need our company, Global Rain, come up ensure the security features of the webpage are secure enough to protect their clients information. For this, we will be securing information being sent form the client to Artemis Financial by encrypting any info being sent back and forth as well as securing a connection with the use of Certificates, keys, and HTTPS. 

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

Dependency cheks are farily easy to generate and although can sometimes be seen as time consuming, can add a lot of value in the form of security in the eyes of clients that may help bring in more potenetial clients or recommendations. This is one of the largest reasons for ensuring that all code is secure and that we minimize the vulnerabilties that exists in code to continue to prevent cyber attacks. A company that maintains it's security practices and that builds a reputation on secure information can add a lot of value to itself by building credibility amongst their own base and building their credibility amongst the community.

What about the process of working through the vulnerability assessment did you find challenging or helpful?

At first, it seemed a bit difficult trying to think about the possible vulnerabilities but the more times it is done, the easier it becomes to really have some quick ideas on what should be looked at first with specific scenarios. I do like that they break it down into these different categories to think about as it can be somewhat of a checklist that you mark off as you go while assessing security of an application or design. 

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

The approach would always begin with the highest priority item that is the most vulnerable based on the scenario. From there, we would add other layers of security that would further increase the prevention of stolen information by having some kind of back up plan. For example, creating a secure connection between the website and the client is important to protect the information being sent back and forth. An additional layer would be encrypting the data that is being sent back and forth so that if the connection is hacked, at least the information itself may be harder to decrypt if that were to happen. I believe that working on more projects and researching how other projects are secured is going to be very important in becoming more aware or more skilled at identifying vulnerabilities and establishing mititgation techniques. 

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

Testing was key here after changes to the code were made as well as continuing to check the dependency reports. After some changes, at times, the code was not functional because certain dependencies were not compatible or other vulnerabilites may have been introduced becuse certain upgrades may have gotten rid of one may have brought on another. Continuing to check that the software is functional and that vulnerabilities are not introduced are key in making changes when trying to resolve certain vernulerabilties. 

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

The maven depenency check tool was very useful in this project and it appears to be a very useful tool that many other programmers utilize to ensure their coding is built. I would definitely attempt to utilize this more often especially if pursuing a postion in cybersecurity. My biggest strength in this project was utilizing ciphers to encrypt and decrypt messages. This appeared to be the easiest thing for me to do in this project while being able to verify that it was functioning correctly and that I feel most confident in. 
