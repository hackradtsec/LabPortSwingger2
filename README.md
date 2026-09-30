# LabPortSwingger2
Lab: Unprotected admin functionality with unpredictable URL

Prática 2: Lab PortSwingger https://portswigger.net/web-security/access-control/lab-unprotected-admin-functionality-with-unpredictable-url

1- O Painel Administrativo é possível acessar sem uma autenticação. Com isso, é possível fazer alterações nos usuários.

2- Primeiro verifiquei na URL usando o robots.txt para encontrar o acesso ao administrador. No robots não tinha nenhuma informação disponível, então verifiquei no código fonte da página e la tinha o usuário na linha 50 do código (adminPanelTag.setAttribute('href', '/admin-pjb8ss');). Com isso, copiei o admin e coloquei na URL, com isso apareceu a opção de excluir os usuários cadastrados.

3 - Neste Lab, diferente do primeiro, não foi tão simples encontrar o usuário admin, mas quem sabe invadir sistemas consegue rapidamente achar a porta de acesso. Recomendação é melhorar a forma de autenticação para dificultar para o invasor.
