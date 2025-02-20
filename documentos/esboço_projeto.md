Objetivos do projeto:
 - O principal objetivo desse projeto é utilizar de criptografia junto da criação de hashs para assegurar a segurança dentro de um ambiente de trabalho que requer um maior nivel da mesma.

TECNOLOGIAS UTILIZADAS:
 - bcrypt v4.2.1: Hashing seguro de senhas;
 - PyJWT 2.10.1: Autenticação via Tokens JWT;
 - cryptography: Implementação de AES V4 e RSA V8.5.

FLUXO BÁSICO DO SISTEMA:
 - Usuário fará o cadastro (senha será armazenada com bcrypt);
 - Usuário faz o login (autenticado com JWT);
 - Usuário envia uma mensagem criptografada com AES;
 - Apenas o destinatário correto pode descriptografar com sua chave RSA.
