# ValidacaoSenha

## Desafio

Você está trabalhando para uma empresa que utiliza extensivamente os serviços da AWS, e após algumas análises a equipe de segurança identificou que algumas senhas dos usuários no IAM são fracas e podem representar um risco à segurança dos dados da empresa. Para resolver esse problema, foi solicitado que você desenvolva um programa capaz de analisar as senhas dos usuários e fornecer uma validação de força com base em critérios predefinidos.

## Requisitos de segurança para a senha:

- A senha deve ter no mínimo 8 caracteres.
- A senha deve conter pelo menos uma letra maiúscula (A-Z).
- A senha deve conter pelo menos uma letra minúscula (a-z).
- A senha deve conter pelo menos um número (0-9).
- A senha deve conter pelo menos um caractere especial, como !, @, #, $, %, etc.

## Entrada

A entrada será uma única string representando a senha que precisa ser validada.

## Saída

Seu programa deve retornar uma mensagem indicando se a senha fornecida pelo usuário atende aos requisitos de segurança ou não, juntamente com um feedback explicativo sobre os critérios considerados.

### Exemplo

| Entrada           | Saída                                                         |
|-------------------|---------------------------------------------------------------|
| 0101              | Sua senha é muito curta. Recomenda-se no mínimo 8 caracteres. |
| 030609saturno*    | Sua senha atende aos requisitos de segurança. Parabéns!       |
| 010203Jupiter     | Sua senha não atende aos requisitos de segurança.             |
