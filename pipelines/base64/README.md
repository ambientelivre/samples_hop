A client of ours was issues with the base64 decoder in the Apache Hop calculator.  
When a word contains accent or special character, the calculator broken the word, as shown below:

"Elegível" turns into  
![image](https://github.com/user-attachments/assets/16e1eea1-859a-4b5b-90b8-c3494b7cfdea)

We have created four optional javascript codes. If you are facing the same issue, you can test the pipeline "decodes64.hpl" and choise the option that works best for you.
