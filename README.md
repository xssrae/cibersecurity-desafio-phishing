# Phishing para captura de senhas em site Clonado

### Ferramentas

- Kali Linux
- setoolkit 

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://www.mirtesnet.com.br/

### Resutados

Originalmente, o desafio instruía para clonar o site do Facebook por meio da url http://www.facebook.com, porém ao tentar meu setookit não localizava os campos do HTML. Portanto, apenas alterei a url e também tentei no navegador Chrome. Desafio concluido com sucesso. 

![Alt text](./site.png "Site clonado")

![Alt text](./senha.png "Captura de senhas")
