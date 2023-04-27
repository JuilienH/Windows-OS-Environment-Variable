# Windows-OS-Environment-Variable
In a python program, we usually will have a database connector where you input all needed paramaters for constructing a connection string. Some are sensitive information or something you don't share, like the password. You can instead put an environment variable with an alias, which is linked to the password hidden in the background. Depending on the operating system you execute your program, this repository shows how you can collaborate scripting with your team members without sharing your personal credential.
## System Properties->Advanced->Environment Variables

![env](https://user-images.githubusercontent.com/22305109/234943862-e7f588cf-fc08-494f-be05-65345fccb66c.PNG)
## System variables->Edit to change the envrionment variable or New to create one
For example, I created the alias for connecting to Snowflake database, I made the name as snow_password, which is used in my python program.

![Capture](https://user-images.githubusercontent.com/22305109/234949789-7c857d4f-29c8-40ba-83ef-11cea2fdcf7e.PNG)
