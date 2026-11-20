# API-001 – Teste de requisição GET com Postman

## Objetivo
Verificar se a API Postman Echo responde corretamente a uma requisição GET com um parâmetro de consulta.

## Ferramenta
Postman

## Método HTTP
GET

## Endpoint
https://postman-echo.com/get

## Parâmetro utilizado
- Chave: nome
- Valor: Catarina

## Passos executados
1. Abrir o Postman.
2. Selecionar o método GET.
3. Informar o endpoint da API.
4. Na aba Parâmetros, preencher nome = Catarina.
5. Clicar em Enviar.
6. Verificar o status HTTP e o corpo da resposta.

## Resultado esperado
A API deve retornar status 200 OK e apresentar o parâmetro nome com valor Catarina no JSON de resposta.

## Resultado observado
A requisição retornou status 200 OK. O endereço enviado apresentou o parâmetro nome=Catarina.

## Status
Parcialmente validado — falta confirmar o valor no corpo JSON da resposta.
