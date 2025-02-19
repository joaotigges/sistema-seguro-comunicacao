COMO SERÁ SEU FUNCIONAMETO QUANDO IMPLEMENTADO:
 - Usuário cria um cadastro, da sua senha, será feito um hash com o bcrypt;
 - A autenticação da senha na área de login será feita pelo PyJWT;
 - A criptografia de todas as mensagens serão feitas com o AES;
 - A proteção das chaves de criptografia será feita com o uso de RSA, assim protegendo as chaves usadas.

O armazenamento de dados nesse caso será efetivamente mais seguro por conta do armazenamento criptografado das chaves, assim garantindo uma chance menor de quebra das chaves de criptografia por conta de sua dupla segurança.

