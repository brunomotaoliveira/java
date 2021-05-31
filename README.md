# java
Conhecimentos  e aprendizados em Java



Configurando o Java no Windows 10

[Baixe o Java JDK](https://www.oracle.com/java/technologies/javase-downloads.html)

![](https://github.com/brunomotadev/java/blob/main/assets/java1.jpg)

Configuração do Ambiente

No Windows, precisamos configurar as variáveis de ambiente para que o Java fique sempre disponível. Para isso acesse: Configurações Avançadas do Sistemas > Aba "Avançado" > clique no botão "Variáveis de Ambiente"

![](https://github.com/brunomotadev/java/blob/main/assets/java2.jpg)

Em "Variáveis do Sistemas", verifique se existe uma variável chamada JAVA_HOME. E se o valor dessa variável contém o caminho para a pasta do JDK.

![](https://github.com/brunomotadev/java/blob/main/assets/java3.jpg)



Edite também a variável Path que está em "Variáveis do Sistema" e acrescente o caminho **%JAVA_HOME%\bin** 

![](https://github.com/brunomotadev/java/blob/main/assets/java4.jpg)



Agora rode o comando: 

```
java -version
```

E se tudo estiver OK, o resultado será esse:
