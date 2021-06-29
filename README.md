# A Look into Password Managers

## Analysis

### Problem Identification

Due to the dangers of unauthorized account access, there has been a growing need for randomly generated passwords. Over time, the security demands for passwords have been growing due to the evolution of password cracking techniques, making login credentials insecure. As a result, companies now offer to store randomly generated for the consumer to access over the web or locally on their machine. I feel this is problematic as there are always risks of data breaches from other companies and data sniffing when retrieving sensitive information from the web. Additionally, I feel the storage of randomly generated passwords locally is problematic as if your own machine were to be accessed by a hacker, they would have access to all the accounts with the details stored on your machine. In the making of this program, I will be exploring the options for the development of a password manager and see how I can avoid or amend these issues. I hope to produce a solution which allows for the use through software but also offering a look into how the information is produced to allow a secondary offline solution if required. I am taking this project for educational use – while this is a real-world issue, hackers find vulnerabilities in programs all the time so this program should not be used for real passwords.
The solution demands a program which the user may use upon receiving a login request to input their passwords. Regarding the computer itself, it must be able to take user input to get passwords specific to a particular login and then output them for the user. Since, this will be intended to use upon receiving a password request it must either operate within the same operating system they are attempting to log into or operate externally so they can bring in the password manager to input this data- in short, it needs to work in pair with the login system.

### Stakeholders

The clients and demographic for this software would be computer and smart phone users of the web and of any secure environment. Of course, I am programming this project for my own use, but I intend to make a secure solution. As computer and smart phone users describe a diverse distribution of people, the stakeholders will be a stratified sample to get the viewpoints of the different types of people who this solution is aimed at.
Since the stakeholders for this project represent a broad group, they will merely be excluded to those who use computers and smart phones to interact with the web. Due to the extent of said diversity I will stratify the sample in terms of age. For the first sample I will select teenagers, then adults over 18 and then those over forty. For each group, I intend to use the assistance of at least one individual for each group. Due to limited time and resources the sample distribution is somewhat lacking however, I think the decision in stakeholders will offer a valuable insight to the development of this project.
To represent the younger generation, the teenagers, I intend to have my brother as stakeholder. He uses both his smart phone and computer with several logins online. From my relation to him, I know how he has struggled with password management in the past, so I feel his insight will be valuable not only from his need to use the software but also in how he may suggest how to make it more approachable for that age bracket. For young adults, I will approach some friends on mine with varying comfort and experience with computers to get a broad scope of the usability and ease of understanding. I assume they will show most comfortable with computers compared to the other elected groups and perhaps will tend toward smart phone applications; I feel they would represent the mass of potential stakeholders. Finally, for the older adult’s portion, I will use parents and some members of my extended family to get input regarding their own comfort. I feel they will find interaction most difficult so I think their view would be valuable as well.

### Why is it suited to a computational solution?

Admittedly, the use of this solution outside of a computer would prevent the interception of them by hackers as the solution would instead be protected by the security of the user. Unfortunately, this does not void all issues: the user may lose this information, or it may become damaged overtime and lose functionality. As well as that, since this information will be used on computer devices, it is ready and convenient for use if stored in that same platform.
Moreover, the solution has several obstructions that will need the power of computing to overcome them. Due to the security concerns of this sensitive information, the solution will likely require encryption or massive amounts of information to conceal information and to ensure it is not used by an unintended user. While I stated prior, I wanted a user’s information available to them offline or without the access of a computer where they could figure out their password without a computer, this is a secondary objective due to the priority of security over access.

### Computational methods that the solution lends itself to

#### Problem Recognition

The overall problem is to find a way to generate a software to store and generate passwords while keeping this sensitive information secure and accessible only for the intended user. The problem of security must be approached by looking at methods hackers may use to obtain sensitive information to keep information secure from unintended third parties. Past the core functionality of the program, the software must be accessible in a user interface to maintain this security and make the interaction with said software easy and convenient for the end user.  

#### Problem Decomposition

The problem can be broken down into a series of smaller problems. This is an idea of what they are:
1.	Encryption of login details in a manner meaning they are secure from unintended third parties.
2.	The accessibility of the program to use alongside the intended login request.
3.	The generation of passwords that would be virtually impossible to crack.
4.	Somehow making login details accessible externally from a computer while maintaining security; the computer program should be more a convenience than a dependence.

Unfortunately, the fourth condition is optional due to the prevalence of security as mentioned before. However, when these conditions are met the process will be completed. Ideally, it will mean a viable password manager is produced to connect a user to their accounts in the ways described above.

#### Divide and Conquer

The problem being decomposed outlines all the challenges demanded by the solution, thus bringing method to the program’s requirements. While challenging in their own right, the use of divide and conquer will join each subproblem to build the solution.

#### Abstraction

When storing sensitive information, we can encrypt it to mask the meaning attached to data so that it is not used by an unauthorised third party. Encryption essentially is the abstraction of meaning from something. In removing the meaning of the data and thus changing it into something useless for interceptors the information is kept secure.

Moreover, I outlined prior that I would want the program to produced passwords that would be virtually impossible to crack. By virtually impossible it means that current hacking techniques would take an extremely long time to crack a password so much so that it is deemed impossible. In this sense, abstraction is used to make the matter of password cracking a statistical matter as opposed to considering the entire situation of the user and their login. Some cracking techniques are trained on dictionaries due to our tendency to use passwords in terms of language. On the other hand, brute force describes the password cracking method which goes over every possibility until finding the original password. Anyway, these describe cracking as a matter of time; the longer a password would take to crack, the stronger it is considered to be.

### Interview

#### Interview questions
