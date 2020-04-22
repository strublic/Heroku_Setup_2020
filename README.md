# Heroku_Setup_2020
Dicas, comandos e utilidades

## Acesso ao database pelo terminal do PC
- heroku pg:reset --remote staging

- heroku run rake db:migrate --remote staging

- heroku run rake db:seed --remote staging
