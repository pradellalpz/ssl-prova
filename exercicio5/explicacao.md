# Exercício 5 – Geração do Certificado

## O que é um Certificado Digital?
O certificado digital é um arquivo que confirma a identidade de uma
pessoa ou servidor. Ele é gerado a partir do CSR e assinado por uma
chave privada.

## Comando executado
- openssl x509 -req -days 365 -in aluno.csr -signkey aluno.key -out aluno.crt
  → gera um certificado autoassinado com validade de 365 dias

## O que é autoassinado?
Neste exercício o certificado foi assinado pela própria chave privada, sem envolver uma Autoridade Certificadora (CA) externa.
Por isso é chamado de self-signed (autoassinado).
