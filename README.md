
<p align="center"> 
      <img src="https://avatars.githubusercontent.com/u/48964967?v=4 width="350px" height="400px"/>
<p align="center"> 

## 💻 Integrador-rms 

o Integrador RMS foi desenvolvido para integrar o módulo Importação de Movimentos do produto RMS-Retail Cloud, tudo que é feito no ponto de venda(PDV) sobe para o concentrador loja e matriz, e o integrador-rms, recebe os movimentos de venda, sangria, nfce e sat e saida operador.
                 
Para a integração com o módulo de Importação de movimentos da TOTVs, estão integrados os seguintes métodos:
- EnviarMovimentos: Método responsável por importar os dados de um ou mais movimentos
- EnviarSangrias: Método responsável por importar sangrias.
- EnviarNFCeSAT: Método responsável por importar NFC-e e SAT.
- EnviarSaidaOperador: Envia as saídas de operadores para serem importadas na base de dados do RMS Retail.

Para fazer a integração entre os produtos é usado o protocolo de comunicação SOAP que permite representar tipos de dados em XML..


## Tópicos

- [Tecnologias](#-Tecnologias)
- [Como executar o e-conect](#-Como-executar-o-e-conect)
- [Features](#-Features)
- [Contribuidores](#-Contribuidores)
- [Autor](#-Autor)
- [Licença](#-Licença)

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

<p align="left"> 
  <a href="https://www.java.com">
    <img src="https://img.shields.io/badge/Java%201.8-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="java">
  </a>
 <a href="https://www.mysql.com">
    <img src="https://img.shields.io/badge/MySQL_v1.7-316192?style=for-the-badge&logo=mysql&logoColor=white" alt="mysql">
  </a> 
 <a href="https://spring.io/projects/spring-boot">
    <img src="https://img.shields.io/badge/Spring_Boot_2.5.1-%6DB33F.svg?&style=for-the-badge&logo=spring&logoColor=white" alt="spring-boot">
  </a>
 </p>

## 🚀 Como executar o e-conect

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
Java JDK 1.8, MySQL 5.7, FTP e SSH
Além disto é bom ter um editor para trabalhar com o código como Eclipse

### 🎲 Executando o e-conect

Abaixo se encontro o link o para o manual de montagem de ambiente e execução.

🚧 Em construção... 🚧

### 🎁 Como liberar um pacote

- Para liberar pacotes para o desenvolvimento do concentrador basta buildar o arquivo Econect-Concentrador/ant/build-econect.conc.xml
- os pacotes .jar são gerados no diretório /usr/socin/econect/conc/lib

- Para liberar pacotes de instalação basta buildar o arquivo Econect-Build/ant/build.xml
- os pacotes .jar são gerados no diretório /usr/socin/econect/build/dist/V_RLS_VERSAO/Econect-Concentrador/instalador

## 💫 Features

O conteúdo referente as features do e-econect se encontra no local  do link abaixo.

https://socincompany.atlassian.net/wiki/spaces/E

## 😃 Autor

<p align="center"> 
   <a href="https://www.socin.com.br/">
      <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/48964967?v=4" width="100px;" alt="socin"/>
   </a>
</p>
<p align="center"> 
      <sub><b>Socin Sistemas</b></sub></a> <a href="https://www.socin.com.br/" title="Socin">🚀</a>
<p align="center"> 
 Feito com ❤️  pela equipe de desenvolvimento Socin Sistemas!
</p>
<p align="center"> 
 <a href="https://www.facebook.com/socinsistemas"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook"></a>
<a href="https://www.linkedin.com/company/socinsistemas/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Linkedin"></a>
<a href="https://www.instagram.com/socinsistemas/?hl=pt-br"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"></a> 
</p>

## 📝 Licença

🚧 Em construção... 🚧

