# Gerador de senhas aleatorias em Python

## Programa em python para gerar senhas aleatórias utilizando criptografia com GnuPG

O que preciso para rodar?

 * Ter o Python 3.x na maquina
    * Caso esteja utilizando Linux, é bem provavel que você já tenha o python em sua maquina rode o seguinte comando:
     ```bash
      $ python --version
          #resutado: Python 3.x
     ```
	ou
      ```bash
      $ python3 --version
          #resutado: Python 3.x
      ```
	Caso não tenha o python instalado rode os seguintes comandos para instala-lo:

      ```bash
      $ sudo apt-get install python3
      ```
* Ter o [pip](https://pt.wikipedia.org/wiki/Pip_(gerenciador_de_pacotes)) instalado
	* execute o seguinte comando para saber se o pip já está instalado:
		```bash
		$ pip3 --version
  		```
      	caso não esteja, use o seguinte comando para instala-lo:
        ```bash
		$ sudo apt-get install -y python3-pip
  		```

* Ter o [GPG](https://www.gnupg.org/) instalado
	* execute o seguinte comando para saber se o gpg já está instalado:
		```bash
		$ gpg --version
  		```
      	caso não esteja, use o seguinte comando para instala-lo:
        ```bash
		$ sudo apt-get install gpg
  		```				
* Instale o [modulo do gpg para Python](https://pythonhosted.org/python-gnupg/)
	* Para isso basta rodar o  seguinte comando:
    	```bash
		$ pip3 install python-gnupg
  		```
* Tenha uma chave GPG
	* caso não tenha, basta seguir [esse tutorial](http://gjuniioor.github.io/blog/gnupg/#gerando-chaves) para gerar uma.

* Agora é só rodar! :wink::metal:
