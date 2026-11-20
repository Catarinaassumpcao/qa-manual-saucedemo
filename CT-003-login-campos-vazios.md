# CT-003 – Login com campos vazios

## Objetivo
Verificar se o sistema impede o login quando os campos de usuário e senha estão vazios.

## Pré-condição
Estar na página de login do SauceDemo.

## Passos
1. Acessar https://www.saucedemo.com/
2. Deixar o campo Username vazio.
3. Deixar o campo Password vazio.
4. Clicar em Login.

## Resultado esperado
O sistema deve impedir o login e informar que o nome de usuário é obrigatório.

## Resultado obtido
O sistema impediu o login e apresentou a mensagem: "Epic sadface: Username is required".

## Status
PASS — Aprovado.
