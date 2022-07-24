# cookie.session.generator
Needed a random cookie session with similar structure and characters generator when doing a CTF,  maybe it helps someone else too.
You can change the number of cookies to generate at *number*, in this file the value of number is 200.
You can change the cookie lenght at lista.append(secrets.token_urlsafe(number)) - secrets.token_urlsafe([nbytes=None]) : This function is responsible for generating a random URL-safe text string containing nbytes random bytes. This is suitable for password recovery applications.
Example : Generate a hard-to-guess temporary URL containing a security token.
Creates a file with every cookie value on a new line \n

![image](https://user-images.githubusercontent.com/79203900/180644260-1033fa22-7553-4600-a3d9-85ac3ec85a90.png)

if you want to change the cookie lenght, you need to play with the secrets.token_urlsafe value. I don't know how, just play with it, until you get your precise value. It works on my computer :)


![image](https://user-images.githubusercontent.com/79203900/180649801-385c279a-9d0d-410b-a6aa-2390119bbbc6.png)
