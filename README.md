# CS-305
Projects from CS-305
Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
  Artemis Financial was a fictitious client that had a web based software sysstem that handled clients financial data.  They wanted to make sure that all of their software was secure from existing secruity threats.
  
What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
  One thing I did well was to research static testing results.  I made sure to throroughly delve through the NVD and check each of the listed vulnerabilities from the dependency report.
  Coding securely is important because while we can always find vulnerabilities and fix them, if our code is secure in the first place, there is that much less of a chance our software is affected.
  Software security adds almost infinite value to a company.  Every time an attack is thwarted, that can save the company untold financial burden from lawsuits, not to mention any criminal burden from negligence.
  
What part of the vulnerability assessment was challenging or helpful to you?
  The assessment as a whole was challenging.  Thinking about preventing malicious intent was a new thread for coding.  Usually I am trying to account for my own misstakes or just making sure the code works for any type of user input, aka making the code user proof.
  Having to think about whether or not my code could be taken advantage of meant adding a new dimension of thought, which was especially hard when an avenue of attack can use code that you are unfamiliar with, such as SQL injection when you don't know SQL.
  
How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
  First, we added the Maven dependency check, which helps to check the countless amount of addons to the project.  Then we do a manual code review to check our own code.  In the future, these two things would be among the techniques I will continue to use.
  
How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
  To ensure functionality was just a process of write some code, test it, repeat.  Secure coding meant thinking about each line of code and taking a look at what was being coded.  Like having a checklist, you go through and make sure to check off everything on the list.  After refactoring, I would do another manual review as well as a new dependency check.
  
What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
  OWASP was invaluable!  The dependency check alone is such a wonderful tool.
  
Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
  I would show them the final report.  It should be a good basis for showing that I can think security as well as form and function when working on a software project.
