# Calculadora WebService Com Axis2

<h4>Finalidade</h4>

O projeto foi iniciado com a intenção de aprender Web Services em Java.

------------



<h4>Programas utilizados</h4>

- Eclipse IDE 2020-12
- jdk1.8.0
- Tomcat 9
- Axis2 1.7.9

------------


<h4>Funcionalidades</h4>

O WebService pode receber quatro requisições:
- Soma: Requisição recebe dois valores do tipo Double e retorna a soma entre os dois.
- Subtração: Requisição recebe dois valores do tipo Double, faz a subtração do primeiro valor passado menos o segundo e retorna o resultado.
- Divisão: Requisição recebe dois valores do tipo Double, faz a divisão do primeiro valor passado pelo segundo e retorna o resultado.
- Multiplicação: Requisição recebe dois valores do tipo Double, multiplica o primeiro valor passado pelo segundo valor e retorna o resultado.

------------


<h4>Configurações</h4>
<h5>Variáveis de ambiente:</h5>

 `Nome = AXIS2_HOME valor = C:\axis2-1.7.9`<br>
`Nome = CLASSPATH valor = .;%AXIS2_HOME%`<br>
`JNome = AVA_HOME valor = C:\Program Files\Java\jdk1.8.0_281`<br>
`Nome = Path valor = %AXIS2_HOME%\bin`<br>

Para funcionamento do código, Devemos colocar uma cópia do arquivo axis2.war na pasta webapps, ela fica dentro da pasta de instalação do tomcat.
Meu Caso: C:\Tomcat\webapps
