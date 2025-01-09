# Apache Hop
## Javascript decoder Base64
A client of ours was issues with the base64 decoder in the Apache Hop calculator.  
When a word contains accent or special character, the calculator broken the word, as shown below:

> [!NOTE]
> "Elegível" turns into  
> <picture>
>  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/ambientelivre/samples_hop/blob/main/images/issue_base64.png">
>  <source media="(prefers-color-scheme: light)" srcset="https://github.com/ambientelivre/samples_hop/blob/main/images/issue_base64.png">
>  <img alt="decode base64 issue example." src="https://github.com/ambientelivre/samples_hop/blob/main/images/issue_base64.png">
>  </picture>


We have created four optional javascript codes. If you are facing the same issue, you can test the pipeline "decodes64.hpl" and choise the option that works best for you.
