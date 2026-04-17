# Exercício 7 – Servidor HTTPS

## Comando executado
python3 -m http.server 8443 --bind 0.0.0.0

## Erro encontrado
SSL_ERROR_RX_RECORD_TOO_LONG — Secure Connection Failed

## Por que ocorre esse erro?
O comando python3 -m http.server cria um servidor HTTP simples,
não HTTPS. Quando o navegador tenta fazer uma conexão SSL/TLS
com o servidor, ele recebe dados HTTP puro em vez de dados
criptografados, causando o erro de registro SSL muito longo.
