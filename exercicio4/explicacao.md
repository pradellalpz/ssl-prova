# Exercício 4 – CSR (Certificate Signing Request)

## O que é um CSR?
O CSR é um arquivo de solicitação de certificado digital. Ele contém
informações sobre o dono do certificado e é enviado para uma
Autoridade Certificadora (CA) para gerar o certificado final.

## Comando executado
- openssl req -new -key aluno.key -out aluno.csr
  → gera um CSR usando a chave privada criada no exercício anterior

## Dados preenchidos
- País: BR
- Estado: Sao Paulo
- Cidade: Piracicaba
- Organização: EEP
- Nome: Lucas Pradella
- Email: lucasppradella@gmail.com
