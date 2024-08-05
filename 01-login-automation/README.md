# Desafio de Programação em Python: Automação de Login e Armazenamento de Sessão

## Objetivo

Criar um script em Python que realiza login no site [Automation Exercise](https://automationexercise.com/login) e salva os cookies e o `localStorage` da sessão para uso em automações futuras.

## Instruções

1. **Realizar Login**:
   - Acesse o site [Automation Exercise](https://automationexercise.com/login).
   - Utilize Python para enviar as credenciais de login e autenticar-se com sucesso.
   - Crie uma conta no site para obter um email e senha válidos.

2. **Salvar Cookies**:
   - Após o login, capture todos os cookies da sessão.
   - Salve-os em um arquivo JSON.

3. **Salvar LocalStorage**:
   - Capture os dados do `localStorage` após o login.
   - Salve-os em um arquivo JSON.

4. **Reutilização dos Dados**:
   - Demonstre que os cookies e o `localStorage` capturados podem ser reutilizados para acessar o site sem precisar efetuar login novamente.

## Critérios de Avaliação

- O script deve realizar o login com sucesso e capturar cookies e localStorage corretamente.
- O código deve ser bem estruturado e fácil de entender.
- Os dados de sessão devem ser reutilizáveis para simular um login persistente.
- As credenciais de login e outras informações sensíveis devem ser gerenciadas através de variáveis de ambiente, utilizando um arquivo .env para garantir a segurança e flexibilidade do código.

## Dicas

- **Verifique o Sucesso do Login**: Após o login, busque elementos únicos que confirmem o acesso à conta, como o botão de logout.
- **Script para Capturar LocalStorage**: Use `JSON.stringify(window.localStorage)` para capturar o conteúdo do `localStorage` com Selenium.
- **Testar Persistência**: Use os cookies e localStorage salvos em uma nova sessão para acessar áreas restritas do site sem autenticar-se novamente.

## Links Úteis

- [Automation Exercise Login Page](https://automationexercise.com/login)
- [Selenium Documentation](https://www.selenium.dev/documentation/en/)
- [Requests Documentation](https://requests.readthedocs.io/en/latest/)

---
Boa sorte e divirta-se com o desafio!