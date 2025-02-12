# CS-305
Classwork submitted for SNHU CS-305


Turning Something In: A guide on submitting your final assignment just for the sake of it


- Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
    Artemis Financial is a global financing company that requires hightened security measures due to the sensitive nature of the data that they handle as part of their business model. In these projects, we harden their web server to provide excellent service to their clients as well as to comply with legal regulation.
- What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
    Using secure code prevents the most common forms of attack that may threaten a company through direct fund loss, denial of service, or loss of reputation. When identifying the vulnerabilites that Artemis Financial was open to, we took steps to document, correct, and prevent these vulnerabilities from arising in the future.
- Which part of the vulnerability assessment was challenging or helpful to you?
    The most challenging part of the vulnerability assessment was taking enough time to sift through the discovered dependency vulnerabilities and determine which ones are relevant to the product. The challenge was not in difficulty, but in time commitment. There are many aspects that play a part in building a modern application, and having enough domain knowledge in each to determine where the vulnerabilities lie, is however, still a difficult task.
- How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
    When thinking of layers of security, it is a good idea to always bear in mind the three cornerstones of industry standard security: authentication, authorization, and accounting. From there, one can decide how to implement these ideas. For instance, when handling sensitive financial information, one wants to make sure that their authentication system only provides credentials to the proper recipient and that their authorization system does not allow access to this data until the user is properly authenticated. 
- How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
    The code underwant static analysis to ensure that vulnerabilities were discovered both before and after security changes were committed. The functionality of the site was tested through "black box" style quality assurance, wherein the tester approached the web server in the manner a typical user would and assessed the output of the system.
- What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
    I always strive to make code modular and reusable by breaking functions down into logically small sub-procedures. This practice enables easy changes to be made to sub-procedures, easy re-use of code in other applicable places, and readily understood code, when given decent naming conventions.
- Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
    I hope that employers do not take interest in these projects, as I am far more proud of my personal projects. That being said, I could utilize the course material as 'proof' that I am familiar with industry-standard secure coding practices.


I have come to realize that as individuals, we often say we value quality over quantity, but as a whole, our society pushes us towards producing only quantity. At every place of employment I have worked, my employer would have been more satisfied with a higher quantity of work than a greater quality. In school, we are told to write essay after essay each week, producing only what is needed to reach the rubriced goals. Venturing further than what is required would prove pointless, as we do not hold passion for this class, rather passion for the subject. All that to say, I would rather be producing high quantities of something useful, rather than what our society demands of us, which in large part, is temporary and pointless, like the paperwork that will never be seen by eyes other than my own, but I am told to complete each day 'in case someone looks at it,' despite the paperwork not having any significant details worth looking for. Ah, what a life we have created for ourselves.
