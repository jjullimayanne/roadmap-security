#### Path traversal, also known as directory traversal or dot dot slash (../) attack, is a security vulnerability that occurs when an application 

[link](https://0a9c007503270b399b4e190d00c20073.web-security-academy.net/)

allows a user to input a file path and doesn't properly validate or sanitize the input. This can lead to an attacker being able to navigate
to directories they shouldn't have access to.

#### portswigge challenge to learn about path traversal:

- I use Burp Suite which is a set of cybersecurity tools designed for web application security testing. 

##### To intercept a Fetch request using Burp Suite

- Configure your browser to use Burp as a proxy, similar to intercepting regular HTTP requests.

- Enable Interception: In Burp Suite, go to the "Proxy" tab and ensure that the "Intercept is on" (the button should be highlighted in green).

- Send a Fetch Request: Trigger the Fetch request from the browser by navigating to a page or executing JavaScript code that makes a Fetch request.

  

- Than When we choose some image we can allow to change the path address request to our file that contains the password





