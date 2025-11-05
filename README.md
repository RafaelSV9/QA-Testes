🧪 Desafio: Testes Manuais no Mundo Ágil
📖 Descrição do Projeto

Este projeto tem como objetivo revisar conceitos úteis de testes manuais e praticar atividades típicas do dia a dia de um QA (Quality Assurance) em um ambiente ágil.
A proposta é compreender o papel do QA dentro das metodologias ágeis, aplicar boas práticas de testes funcionais e construir uma base sólida para atuação profissional na área.

🎯 Objetivos de Aprendizagem

Entender o papel do QA no contexto ágil.

Criar e executar casos de teste manuais funcionais.

Utilizar boas práticas na reportagem e documentação de bugs.

Compreender o ciclo completo de qualidade de software.

Adotar uma mentalidade colaborativa e preventiva (Shift Left).

⚙️ Conceitos-Chave
Papel do QA no Ágil

O QA não é apenas o testador, mas o garantidor da qualidade durante todo o ciclo de desenvolvimento.
Ele atua lado a lado com desenvolvedores, POs e Scrum Masters, ajudando a:

Validar histórias de usuário e critérios de aceitação.

Detectar falhas antes de chegarem ao usuário final.

Garantir entregas com valor e estabilidade.

Tipos de Testes Manuais
Tipo de Teste	Descrição
Funcional	Verifica se o sistema faz o que foi especificado.
Regressão	Confirma se novas mudanças não quebram funções antigas.
Integração	Garante a comunicação entre módulos e sistemas.
Aceitação (UAT)	Valida se o sistema atende às expectativas do usuário.
Smoke Test	Testa rapidamente se o sistema “sobe” e funciona minimamente.
🧩 Artefatos de QA

Plano de Teste: define o escopo e as estratégias de teste.

Casos de Teste (CT): descrevem as etapas de execução.

Relatório de Bug: documenta falhas e comportamentos inesperados.

Matriz de Rastreabilidade: liga requisitos → testes → resultados.

🧠 Boas Práticas

Testar o quanto antes (Shift Left).

Comunicação constante com devs e POs.

Registrar evidências visuais (prints, vídeos).

Documentar tudo de forma clara e padronizada.

Priorizar a experiência do usuário final.

🧰 Ferramentas Recomendadas
Categoria	Ferramentas
Gerenciamento de Testes	TestLink, Zephyr, Qase
Gestão de Tarefas / Bugs	Jira, Trello, Azure DevOps
Captura de Evidências	ShareX, Lightshot, OBS Studio
🧪 Atividade Prática
1. História de Usuário

Como usuário, quero realizar login com e-mail e senha para acessar meu painel pessoal.

Critérios de Aceitação:

Deve validar e-mail e senha corretamente.

Exibir mensagem de erro em caso de credenciais inválidas.

Redirecionar para a página inicial após login bem-sucedido.

2. Caso de Teste (exemplo)
ID	Descrição	Passos	Resultado Esperado	Status
CT001	Validar login com credenciais corretas	1. Abrir tela de login
2. Inserir e-mail válido
3. Inserir senha válida
4. Clicar em "Entrar"	Usuário é autenticado e redirecionado ao dashboard	✅ Passou
CT002	Validar mensagem de erro para senha incorreta	1. Inserir e-mail válido
2. Inserir senha incorreta
3. Clicar em "Entrar"	Exibir mensagem “Usuário ou senha inválidos”	⚠️ Falhou
3. Relatório de Bug (exemplo)

Título: Mensagem de erro incorreta ao inserir senha inválida
ID: BUG001
Prioridade: Alta
Severidade: Média
Passos para reproduzir:

Acessar tela de login.

Inserir e-mail válido.

Inserir senha incorreta.

Clicar em “Entrar”.

Resultado atual: Página é recarregada sem exibir mensagem de erro.
Resultado esperado: Exibir “Usuário ou senha inválidos”.
Evidência: bug001_screenshot.png
Status: Aberto

🗂️ Estrutura Recomendada de Repositório
📁 qa-desafio-agil
 ┣ 📄 README.md
 ┣ 📄 plano-de-teste.md
 ┣ 📄 casos-de-teste.xlsx
 ┣ 📄 relatorio-de-bugs.pdf
 ┗ 📄 evidencias/
     ┣ 📸 bug001_screenshot.png
     ┗ 📸 bug002_video.mp4

🧭 Conclusão

Este desafio demonstra como o QA atua dentro do ciclo ágil, garantindo que qualidade seja uma responsabilidade compartilhada.
Mais do que encontrar erros, o QA ajuda o time a entregar valor contínuo e melhorar o produto a cada sprint. 🚀
