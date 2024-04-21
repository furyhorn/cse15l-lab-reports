## Part1
**Code for ```ChatServer```**
![image](https://github.com/furyhorn/cse15l-lab-reports/blob/main/code.png)

<br>
<br>


**Using ```/add-message```**
![image](https://github.com/furyhorn/cse15l-lab-reports/blob/main/AM1.png)

**Which methods in your code are called:**<br>
handleRequest(URI url): This method of the Handler class is called when a request is received.<br>
**What are the relevant arguments to those methods, and the values of any relevant fields of the class:**<br>
relevant arguments:```URI url``` The URI for the request would be something like ```/add-message?s=Hello&user=jpolitz```.<br>
relevant fields: ```String content``` Initially, this field is an empty string ```""``` in the Handler class.<br>
**How do the values of any relevant fields of the class change from this specific request? If no values got changed, explain why:**<br>
After processing the request, the method parses the query string ```s=Hello&user=jpolitz```.
The content field is updated to ```jpolitz: Hello\n```.
Thus, the field content changes from ```""``` to ```"jpolitz: Hello\n"```.
<br>
<br>
<br>

![image](https://github.com/furyhorn/cse15l-lab-reports/blob/main/AM2.png)

**Which methods in your code are called:**<br>
handleRequest(URI url): This method is called again with the new request.<br>
**What are the relevant arguments to those methods, and the values of any relevant fields of the class:**<br>
relevant arguments:```URI url``` The URI for this request would be something like ```/add-message?s=How are you&user=yash```.<br>
relevant fields: ```String content``` Before this call, it holds the value ```jpolitz: Hello\n``` from the previous request.<br>
**How do the values of any relevant fields of the class change from this specific request? If no values got changed, explain why:**<br>
The method processes the new query string ```s=How are you&user=yash```.
The content field is updated by appending ```yash: How are you\n```.
The field content changes from ```jpolitz: Hello\n``` to ```jpolitz: Hello\nyash: How are you\n```.

## Part2
![image](https://github.com/furyhorn/cse15l-lab-reports/blob/main/lsPrivateKey.png)
![image](https://github.com/furyhorn/cse15l-lab-reports/blob/main/lsPublicKey.png)
![image](https://github.com/furyhorn/cse15l-lab-reports/blob/main/remoteConnection.png)


## Part3
In the labs from weeks 2 and 3, I learned how to use SSH keys for secure, passwordless access to remote servers. I also discovered the practical use of the `scp` command for securely transferring files between my computer and a remote server, using encrypted connections to manage files safely and efficiently.
