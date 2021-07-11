# A Look into Password Managers

## Analysis

### Problem Identification

Due to the dangers of unauthorized account access, there has been a growing need for randomly generated passwords. Over time, the security demands for passwords have been growing due to the evolution of password cracking techniques, making login credentials insecure. As a result, companies now offer to store randomly generated for the consumer to access over the web or locally on their machine. I feel this is problematic as there are always risks of data breaches from other companies and data sniffing when retrieving sensitive information from the web. Additionally, I feel the storage of randomly generated passwords locally is problematic as if your own machine were to be accessed by a hacker, they would have access to all the accounts with the details stored on your machine. In the making of this program, I will be exploring the options for the development of a password manager and see how I can avoid or amend these issues. I hope to produce a solution which allows for the use through software but also offering a look into how the information is produced to allow a secondary offline solution if required. While this is a real-world issue, hackers find vulnerabilities in programs all the time so this project may be restricted to use a narrower band of methods as I will not be updating the project to protect against current security concerns; primarily, this is an educational exploration.
The solution demands a program which the user may use upon receiving a login request to input their passwords. Regarding the computer itself, it must be able to take user input to get passwords specific to a particular login and then output them for the user. Since, this will be intended to use upon receiving a password request it must either operate within the same operating system they are attempting to log into or operate externally so they can bring in the password manager to input this data- in short, it needs to work in pair with the login system.

### Stakeholders

The clients and demographic for this software would be computer and smart phone users of the web and of any secure environment. Of course, I am programming this project as an educational pursuit, but I intend to make a secure solution. Of course, I will have the project reviewed by cyber security experts before interacting with stakeholders to ensure their experience with the solution will not impact their online security; I intend to have users interact with a simulative system where they attempt to login to a service as opposed to their real accounts. This way, security is not a concern as the password manager tool is not used for real life applications. Back to the stakeholders, as computer and smart phone users describe a diverse distribution of people, the stakeholders will be a stratified sample to get the viewpoints of the different types of people who this solution is aimed at.
Since the stakeholders for this project represent a broad group, they will merely be excluded to those who use computers and smart phones to interact with the web. Due to the extent of said diversity I will stratify the sample in terms of age. For the first sample I will select teenagers, then adults over 18 and then those over forty. For each group, I intend to use the assistance of at least one individual for each group. Due to limited time and resources the sample size and distribution is less representative than desired. However, I think the decision in stakeholders will offer a valuable insight to the development of this project nonetheless.
To represent the younger generation (the teenagers) I intend to have one stakeholder. This age bracket is known to use both their smart phones, computers and games consoles with several logins online. Particularly, in my experiences I am aware of how this group tends to struggle with password management so I feel their insight will be valuable not only from their need to use the software but also in how they may suggest how to make it more approachable for that age bracket. To represent this group, I will pick a certain family member. For young adults, I will approach some friends on mine with varying comfort and experience with computers to get a wider scope of the usability and ease of understanding. I assume they will show to be the most comfortable group with computers compared to the other elected groups and perhaps will tend toward smart phone applications of this project; I feel they would represent the mass of the target demographic. Finally, for the older adult’s portion, I will again look within my family to get input regarding their own comfort. I feel they will find interaction most difficult so I think their view would be valuable as well.

### Why is it suited to a computational solution?

Admittedly, the use of this solution outside of a computer would prevent the interception of them by hackers as the solution would instead be protected by the security of the user. Unfortunately, this does not void all issues: the user may lose this information, or it may become damaged overtime and lose functionality. As well as that, since this information will be used on computer devices, it is ready and convenient for use if stored in that same platform.
Moreover, the solution has several obstructions that will need the power of computing to overcome them. Due to the security concerns of this sensitive information, the solution will likely require encryption or massive amounts of information to conceal information and to ensure it is not used by an unintended user. While I stated prior, I wanted a user’s information available to them offline or without the access of a computer where they could figure out their password without a computer, this is a secondary objective due to the priority of security over access.

### Computational methods that the solution lends itself to

#### Problem Recognition

The overall problem is to find a way to generate a software to store and generate passwords while keeping this sensitive information secure and accessible only for the intended user. The problem of security must be approached by looking at methods hackers may use to obtain sensitive information to keep information secure from unintended third parties. Past the core functionality of the program, the software must be accessible in a user interface to maintain this security and make the interaction with said software easy and convenient for the end user.  

#### Problem Decomposition

The problem can be broken down into a series of smaller problems. This is an idea of what they are:
* Encryption of login details in a manner meaning they are secure from unintended third parties.
* The accessibility of the program to use alongside the intended login request.
* The generation of passwords that would be virtually impossible to crack.
* Somehow making login details accessible externally from a computer while maintaining security; the computer program should be more a convenience than a dependence.

Unfortunately, the fourth condition is optional due to the prevalence of security as mentioned before. However, when these conditions are met the process will be completed. Ideally, it will mean a viable password manager is produced to connect a user to their accounts in the ways described above.

#### Divide and Conquer

The problem being decomposed outlines all the challenges demanded by the solution, thus bringing method to the program’s requirements. While challenging in their own right, the use of divide and conquer will join each subproblem to build the solution.

#### Abstraction

When storing sensitive information, we can encrypt it to mask the meaning attached to data so that it is not used by an unauthorized third party. Encryption essentially is the abstraction of meaning from something. In removing the meaning of the data and thus changing it into something useless for interceptors the information is kept secure.

Moreover, I outlined prior that I would want the program to produced passwords that would be virtually impossible to crack. By virtually impossible it means that current hacking techniques would take an extremely long time to crack a password so much so that it is deemed impossible. In this sense, abstraction is used to make the matter of password cracking a statistical matter as opposed to considering the entire situation of the user and their login. Some cracking techniques are trained on dictionaries due to our tendency to use passwords in terms of language. On the other hand, brute force describes the password cracking method which goes over every possibility until finding the original password. Anyway, these describe cracking as a matter of time; the longer a password would take to crack, the stronger it is considered to be.

### Interview

#### Interview questions

The questions I will ask each stakeholders will concern their experiences with regard to password keeping and account security. I will go over current techniques and try to build a notion of the issues with today's current solutions. I will take a semi-structured approach meaning I will follow the questions stated below but follow up on any points I feel need exploring. This technique will resemble a conversation which will be beneficial to try to understand the perceptions around the problem of password keeping.

1. How would you describe your comfort with computers and mobile phones?
2. In relation to password keeping, do you remember your own passwords or use external resources to access your accounts
3. Have you noticed a change in account security requirements in recent years? If so, how do you feel about these changes?
4. How would you describe the security of your own passwords and accounts?
5. Do you use any password managers?
6. If you were away from your home and devices and were asked to login to one of your accounts, how confident are you that you would manage?
7. Do you have your own ideas as to how to resolve this issue? What would you look for in the solution?
8. What kinds of services do you have accounts for?
9. Do you have anything else to add?

Here is the Google [form](https://forms.gle/Hpycs4xxTLPN6YtZA)
#### Interview results

##### How would you describe your comfort with computers and mobile phones?
###### **Under 18**
> I'm okay with them.
> -N
###### **Under 30**
> I have the basics down but I tend to struggle quite often with the smaller details.
> -H

> Decent.
> -T
###### **Over 30**
> Fair.
> -A

> Not very comfortable - enough to get along with.
> -T

##### In relation to password keeping, do you remember your own passwords or use external resources to access your accounts?
###### **Under 18**
> I remember my passwords.
> -N
###### **Under 30**
> I remember my own but take into account the suggested styles.
> -H

> External sources.
> -T
###### **Over 30**
> Remember some, use digital memory for some and will generate new for some.
> -A

> I have a system for remembering passwords but it is a very insecure one.
> -T

##### Have you noticed a change in account security requirements in recent years> If so, how do you feel about these changes?
###### **Under 18**
> No.
> -N
###### **Under 30**
> Passwords have to be much more complex and some know when you've used passwords for different sites and require a completely new one which is harder for me to remember.
> -H

> It requires more 'unique' characters in a password for it to be accepted which makes it more difficult to remember.
> -T
###### **Over 30**
> Mixed feelings. Sometimes it's too much security sometimes not enough.
> -A

>They are more hopes to jump through and a lot of code recognition requests that mean that if you are not in possession of your mobile phone there is not a lot you can do in my experience, particularly if you are in the pocket of Google.
> -T

##### How would you describe the security of your own passwords and accounts?
###### **Under 18**
> They are good passwords, complicated.
> -N
###### **Under 30**
> I repeat passwords with slight changes but they are somewhat complex.
> -H

> Not very sure, my passwords are often the same across multiple accounts with slight variations to them.
> -T
###### **Over 30**
> Fair.
> -A

> Atrocious.
> -T

##### Do you use any password managers?
###### **Under 18**
> No.
> -N
###### **Under 30**
> No.
> -H

> No.
> -T
###### **Over 30**
> Yes.
> -A

> No.
> -T

##### If you were away from your home and devices and were asked to login to one of your accounts, how confident are you that you would manage?
###### **Under 18**
> 4/5.
> -N
###### **Under 30**
> 3/5.
> -H

> 1/5.
> -T
###### **Over 30**
> 3/5.
> -A

> 1/5.
> -T

##### Do you have your own ideas as to how to resolve this issues? What would you look for in the solution?
###### **Under 30**
> Some sites to require you to always input your password so you don't rely on your device remembering it when you face a new one.
> -H

> For it to be available on my phone and PC and updates when any changes are made.
> -T
###### **Over 30**
> Write em down, analog style.
> -A

> I don't believe that there is much choice not to have your mobile phone because the security step insists that you read back a code sent to your mobile phone. If I sign in on a public computer I need my mobile phone or can't do a thing.
> -T

##### What kinds of services do you have accounts for?
###### **Under 18**
> Games, revision sites.
> -N
###### **Under 30**
> Music, social media, banks, education.
> -H

> Entertainment, google, online banking
> -T
###### **Over 30**
> Varied.
> -A

> Peer to peer selling sites: Depop, Vinted, Amazon, eBay, Google Photos.
> -T

##### Do you have anything else to add?
###### **Over 30**
> Google now notifies me when I use the same password for multiple sites. I suspect this is phishing
> -A

#### Analysis of results

### Research
