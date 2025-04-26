# SoftwareSec
4/26/2025

The Client for this course was Artmeis Financial, a finance company that deals with customers investments, retirement savings, and insurance. The issue they were having is that they were looking for a way to encrypt and secure their long term archive files in order to protect them from outside actors.

I think what I did well to assist the company with their issue was the initial manual review of the code base: Finding the issues in the code itself, the static testing that discovered dependency issues, and the follow up mitigation plan to resolve those issues. Coding securely is important because any flaws in the application are potential doorways to security issues and possible instrusions or theft. Having strong and secure applications can help set a company above the rest. If customers know that the applications they use to interact with the company won't be broken easily and their data and information won't be stolen, they are more likely to continue to do business with that company in the future. 

The hardest part of the vulnerability assessment for me was in the followup assignments trying to determine which depenedencies were actually false positive and which weren't. Once I figured out the key to making that determination, it went a lot smoother. But without knowing what you're looking for, it can be difficult.

We increased the security of the program by creating and implementing SSL certificates and passing data with encyptions and hasing methods. Using RSA and SHA-256 to encrypt and hash data helps to keep information secure both in transmission/receiving, and for locking files for storage. Along with the dependency checks and code reviews, using encrypted traffic in applications is a great mitigation technique to prevent data and/or information loss and to keep an application secure. 

The amount of resources available to programmers for them to write and maintain secure code is endless. Websites like StackOverflow, Reddit, and GitHub are great for finding answers to questions you may have. The documentation for the repositories and language you use can help you figure out what everything does, how it calls different repositories and how it handles variables and operations. IDEs like Eclipse, the JetBrains Suite of IDEs, and VisualStudio are great tools that have available to them numerous plugins and addon to making coding easier and smoother and allow a programmer to write better and more secure code.

I think the best examples of work from this course would be the First Project which involved the code review and original mitigation report. I think I did a good job combing over the code and finding issues that were potenially going to be issues down the road, had they not been fixed.

