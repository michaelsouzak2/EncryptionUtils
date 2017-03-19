# EncryptionUtils
API Java para criptografar textos em claro.
Esta API permite a criptogrifia de texto plano e utiliza duas abordagens: HEX ou OCTAL.<br /><br />

Requisitos: Java 6 ou superior<br />

--<b>Baixando do repository para o seu PC:</b><br />
  Faça o download do git: <br />
  (Linux) sudo apt-get install git<br />
  (Windows) Instale o git bash

  Faça o clone do repositório: git clone https://github.com/MichaelSSantos/EncryptionUtils.git

--<b>Utilizando a API EncryptionUtils:</b><br/>
Se criptografia hexadecimal:<br />
Algorithm alg = AlgorithmFactory.getInstance("HEX");
<br /><br />

Se criptografia octal:<br />
Algorithm alg = AlgorithmFactory.getInstance("OCTAL");

Use o método encrypt para criptografar o texto.<br />
String cifrado = alg.encrypt("Texto em claro");

Use o método decrypt para decriptografar o texto.<br />
String textoClaro = alg.decrypt(cifrado);
