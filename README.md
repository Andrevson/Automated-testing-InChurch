# Prejeto de Teste automatizado 

## Descrição 

Realizar cadastro na pagina do Inchurch, com preenchimento de dados básicos como Nome, Email, Senha e Confirmação de senha (campos obrigatórios), assim como Nome da igreja (campo não obrigatório).

## CASOS DE TESTE

## Pré condições 

- O email deve ser valido e não cadastrado no sistema
- A senha deve ter 8 dígitos ou mais
- A confirmação da senha deve ser igual a preenchida no campo "Senha"

## Objetivo do teste

- Checar se o usuário consegue realizar um novo cadastro com sucesso.

## Passos e Resultados

- Acessar a página home do site e clicar no botão "Fazer login ou se inscrever" => Sistema retorna com tela de login
- Clicar no campo "Registre-se" => Sistema retorna com a proxima página para preecher os campos necessarios
- Usuário preenche todos os campos corretamente e clica no botão "Criar conta" => Sistema retorna com mensagem "Conta criada com sucesso"
