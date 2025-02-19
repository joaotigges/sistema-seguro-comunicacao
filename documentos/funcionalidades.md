De forma simples o projeto fará:
 - Cadastro de usuários, protegendo a senha com bcrypt antes de armazenar;
 - Login: se a senha estiver correta, gera um Token JWT;
 - Enviar a mensagem: a mensagem é criptografada com AES antes de ser salva;
 - Receber a mensagem: o usuário descriptografa com RSA sua chave AES e acessa a mensagem.
