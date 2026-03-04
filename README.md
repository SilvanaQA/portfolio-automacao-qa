# portfolio-automacao-qa
Portfólio demonstrativo de Engenharia de Qualidade: Arquitetura de testes automatizados (Web &amp; API) utilizando Cypress, padrões de projeto (POM) e CI/CD.

🚀 QA Automation Framework - Web & API📌 Sobre o ProjetoEste repositório é um portfólio de demonstração das minhas habilidades em Engenharia de Qualidade e Automação de Testes.Devido a rigorosos acordos de confidencialidade (NDA) em meus 6 anos de atuação no setor bancário (Bradesco), códigos reais de produção não podem ser expostos. Portanto, este framework foi construído do zero para testar aplicações públicas (ex: Swag Labs / Restful-Booker), demonstrando as melhores práticas de mercado que utilizo no meu dia a dia.

🏗️ Arquitetura e Padrões de ProjetoO framework foi estruturado focando em escalabilidade, fácil manutenção e execução rápida em esteiras de CI/CD:Page Object Model (POM): Separação clara entre a lógica de negócio (ações na página) e os scripts de teste, facilitando a manutenção caso mapeamentos de tela mudem.Data-Driven Testing (DDT): Uso de arquivos fixtures (JSON) para injeção de massa de dados dinâmicos nos testes.Shift-Left Testing: Testes de API isolados rodando antes dos testes de UI para feedback rápido (Fail Fast).Custom Commands: Criação de comandos customizados para ações repetitivas (como Login ou Geração de Token Auth).

🛠️ Stack TecnológicaWeb/UI AutomationFerramenta Principal: Cypress / PlaywrightLinguagem: JavaScript / TypeScriptRelatórios: Allure Report / MochaAwesomeAPI AutomationFerramenta: REST Assured / Postman (Newman)Validações: Contratos JSON Schema, Status Code, Response Body.CI/CD (Integração Contínua)Pipeline: GitHub Actions configurado para rodar os testes automaticamente a cada Push ou Pull Request na branch principal.


Instale as dependências:npm install
Para rodar os testes em modo Headless (background):npx cypress run
Para abrir a interface visual de testes:npx cypress open
📊Estrutura de Diretórios📦 qa-automation-framework


 ┣ 📂 cypress
 ┃ ┣ 📂 e2e            # Cenários de teste organizados por funcionalidade
 ┃ ┣ 📂 fixtures       # Massa de dados (JSON)
 ┃ ┣ 📂 support        # Comandos customizados e Page Objects
 ┃ ┗ 📂 reports        # Relatórios de execução gerados automaticamente
 ┣ 📜 cypress.config.js # Configurações base do framework (BaseURL, Timeouts)
 ┣ 📜 package.json     # Dependências do projeto Node.js
 ┗ 📜 README.md
 
👩‍💻 AutoraSilvana Gomes Especialista em QA & Automação | CPA-20 LinkedIn | silgomes18@gmail.com
