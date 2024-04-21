## Part1
**Code for ```ChatServer```**
![image](https://github.com/furyhorn/cse15l-lab-reports/assets/165836763/e891bf14-620a-4dd3-abda-019e9ac9d803)


<br>
<br>


**Using ```/add-message```**
![image](https://github.com/furyhorn/cse15l-lab-reports/assets/165836763/09fcc4a8-cc57-4632-8662-8382d3d01712)


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

![image](https://github.com/furyhorn/cse15l-lab-reports/assets/165836763/b3c5bf09-beb7-4f16-8116-6a65f365be2b)


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
![image](https://github.com/furyhorn/cse15l-lab-reports/assets/165836763/e0e6c793-a6f4-49f7-a507-88796fe4aaad)
![image](https://github.com/furyhorn/cse15l-lab-reports/assets/165836763/9819f1d5-c877-40a0-a049-45c44362d201)
![image](https://github.com/furyhorn/cse15l-lab-reports/assets/165836763/58fbd390-8a73-4e06-aed4-cd4ec074c3a1)



## Part3
In the labs from weeks 2 and 3, I learned how to use SSH keys for secure, passwordless access to remote servers. I also discovered the practical use of the `scp` command for securely transferring files between my computer and a remote server, using encrypted connections to manage files safely and efficiently.
