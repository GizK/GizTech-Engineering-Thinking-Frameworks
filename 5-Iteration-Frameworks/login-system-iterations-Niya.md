##### **Task**: Documenting three iterations of improving a login system.







###### **Iteration 1: Basic login (username + password)**



**What changed?**

Without a basic login system, the software operates as a locally-installed application. This means that multiple people were forced to share the same files, settings, and saved data.



**Why it improved the system:** The introduction of a basic login feature allows creation of multiple accounts per device. Usernames are unique to every account, and the password ensures that only the owner (or trusted individuals) can access it. The option to save data to the cloud enables the same account to be accessed on another device. 

Many people in a shared location can access the software at the same time, via different devices. No one has to "wait for their turn".



**Any trade-offs introduced:** Poorly implemented logins can be vulnerable to phishing, credential stuffing etc. Mass data breaches can occur, where attackers could obtain thousands of emails, passwords, personal details, etc. This could spell legal trouble both for the company and the public as a whole. The addition of a login increases memory usage, as well as maintenance costs.





###### **Iteration 2: Password strength + lockout rules**



**What changed?**

Password strength ensures that "weak" passwords like "12345" or "Password" are not accepted by the system, which improves security. A lockout only allows a fixed number of attempts for entering the correct password, before the account is locked for a given period of time. This ensures that a potential threat (like a person with malicious intentions) doesn't "accidentally" stumble upon, say, the right combination of 4 digits that will grant them access to their target account.



**Why it improved the system:** Users can be notified via email, for instance, if their account has been locked--- when, where and the device on which it occurred. Lockout rules can standardize how credentials are handled across teams, devices and integrations, reducing inconsistent practices. Documented password and lockout rules can make it easier to demonstrate compliance with privacy or security frameworks and to pass security audits. It also improves user trust.



**Any trade-offs introduced:** Attackers might deliberately try to lock users out. Complex passwords are easier to forget, and some users may even give up creating a password if meeting the requirements take too long/is tedious. Strict authorization rules take more time to follow, especially when working across multiple teams.





###### **Iteration 3: Two-factor authentication**



**What changed?**

After the user enters their username and password, the system asks for a second verification; such as a one-time code, an approval in an authenticator app, a fingerprint scan, etc. 



**Why it improved the system:** 2FA (2-Factor Authentication) adds additional protection to your account against attacks, and especially if your password has been stolen. Automated systems that repeatedly guess passwords dace a second factor, making large-scale account-guessing attacks far less effective. It increases security risk against phishing, identity theft, etc.



**Any trade-offs introduced:** Introduction of a 2FA increases login friction. If the device on which the MFA is unavailable, users may be locked out unless they configured backups. If there is no cell signal, then users might be unable to access their account.







