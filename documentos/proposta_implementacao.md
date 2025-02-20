Explicação de como cada tecnologia será usada no sistema 

 -bcrypt - a tecnologia bcrypt será utilizada na autenticação dos usuários para armazenar senhas de forma segura. Ao registrar um novo usuário e na autenticação do Usuário. 
 -PyJWT - Gerar tokens de autenticação quando um usuário se autentica com suas credenciais (login e senha)
 -Cryptography - Biblioteca onde se encontram ferramentas para criptografia simétrica e assimétrica, como os algoritmos AES e RSA. Ambos podem ser utilizados para proteger a comunicação e os dados sensíveis dentro do Sistema.
 
 - Usuário cria um cadastro, da sua senha, será feito um hash com o bcrypt;
 - A autenticação da senha na área de login será feita pelo PyJWT;
 - A criptografia de todas as mensagens serão feitas com o AES;
 - A proteção das chaves de criptografia será feita com o uso de RSA, assim protegendo as chaves usadas.

O armazenamento seguro de dados é crucial nesse contexto para proteger informações sensíveis, como senhas, mensagens e chaves criptográficas, contra acessos não autorizados. Mesmo em caso de vazamento ou invasão do banco de dados, técnicas como hashing de senhas, criptografia de mensagens e proteção das chaves garantem que os dados permaneçam inacessíveis ou inúteis para atacantes. Isso preserva a confidencialidade e integridade das informações dos usuários, evitando que dados sensíveis sejam expostos ou utilizados de forma indevida.

