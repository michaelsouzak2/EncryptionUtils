# EncryptionUtils
API Java para criptografar textos em claro.

Esta API permite a criptogrifia de texto plano e utiliza duas abordagens: HEX ou OCTAL.

--Baixando do repository para o seu PC:
  Faça o download do git: 
  (Linux) sudo apt-get install git
  (Windows) Instale o git bash

  Faça o clone do repositório: git clone https://github.com/MichaelSSantos/EncryptionUtils.git

--Utilizando a API EncryptionUtils:
Se criptografia hexadecimal:
Algorithm alg = AlgorithmFactory.getInstance("HEX");

Se criptografia octal:
Algorithm alg = AlgorithmFactory.getInstance("OCTAL");

//Use o método encrypt para criptografar o texto.
String cifrado = alg.encrypt("Texto em claro");

//Use o método decrypt para decriptografar o texto.
String textoClaro = alg.decrypt(cifrado);
