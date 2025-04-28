# Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial was seeking someone who was proficient enough in adding encryption/decryption to their program so that they could transfer loads of files in and out of storage safely and efficiently. They wanted to be able to trasnfer multiple files over a short period, so we had to work around that issue by finding an encryption cipher that had a high bit intake, all the while being secure.

# What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
Given the printed vulnerability reports, we found a way to revert the vulnerability by adding extra layers of security using previous encounters with said vulnerability as a learning opportunity. Making sure your code is secure plays a huge role in pushing code into production as you dont want competitors seeing how things are done behind the scenes, and you definitely dont want hackers finding out how they can exploit your program. Software security allows the company's well-being to be a lot less stressful, as you can rule many things out when your code base is secure.

# Which part of the vulnerability assessment was challenging or helpful to you?
False positives were the most confusing part for me to handle, as it was tricky to discern which ones were false positives and, if so, why, and how to fix them.

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
We increased layers of security by adding an encryption/decryption function to the code base, allowing Artemis Financial to securely transfer important files in and out of storage securely. In the future, I plan to use previous encounters with vulnerabilities or encounters others have had with said vulnerabilities to steer us in a better and safer direction.

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
We made sure the software was secure by actually running the code ourselves, which in the end produced vulnerability reports showing us where we went wrong and how to fix said vulnerabilities. 

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
We used the Maven dependency check tool to help us find vulnerabilities in our code. This is a tool I definitely plan to implement in the future as it does most of the hard work for you.

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I plan to show future employers how we went from a vulnerability-riddled code base to a more secure one using industry-standard everyday tools, proving experience and perseverance when it comes to securing programs.
