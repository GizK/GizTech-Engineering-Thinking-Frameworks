First Iteration: Basic login (username + password)
What changed
- Provided a secure means of accessing data
- Allows admin to grant permissions to who can access the data
Why it improved the system
- Before a basic login, anyone could access the system and change the contents of the data and exploit it
- A basic login acts as a security barrier to bad actors and prevents the exploitation of this data
Any trade-offs introduced
- There won't be as much freedom to work on a system, you would have to go through a whole log in system before being allowed to access the site/data
- Admin would have to set up the log in system and provide all workers with new usernames and passwords in a secure way

Second Iteration: Password strength + lockout rules
What changed
- Password must meet a strict critieria before being accepted on the system
- If password is entered or tried more than 3 times, user is locked out of the system
Why it improved the system
- Prevents brute force attacks that could easily find the password
- It safeguards the user and the systems data from falling into the wrong hands
Any trade-offs introduced
- More time needed to unlock user accounts, users may find the system harder to access and may forget passwords quicker

Third Iteration: Two-factor authentication
What changed
- Quick and easy way to double check and authorise users
- Allows users to login through a code sent to their phone or an authentication app
Why it improved the system
- Completely secures the system from key logging devices and brute force attacks
Any trade-offs introduced
- Harder to access system without another device around, relies on another device
- Authentication can be exploited if done through a third party app
