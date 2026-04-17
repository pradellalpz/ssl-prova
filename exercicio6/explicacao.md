# Exercício 6 – SCP (Secure Copy Protocol)

## O que é o SCP?
O SCP é um protocolo de transferência segura de arquivos entre
computadores via SSH. Ele criptografa tanto os dados quanto
as credenciais durante a transferência.

## Comando executado
scp /etc/ssl/certificates/aluno.crt vboxuser@10.0.0.2:/etc/ssl/certificates/

## Explicação do comando
- /etc/ssl/certificates/aluno.crt → arquivo de origem
- vboxuser@10.0.0.2 → usuário e IP da máquina destino
- :/etc/ssl/certificates/ → pasta de destino na segunda VM

## Resultado
Arquivo transferido com sucesso — 100% 1359 bytes a 1.8MB/s
