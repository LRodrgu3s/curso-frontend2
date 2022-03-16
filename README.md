# curso front-end2
### EBAC

# GIT
## Conceitos de versionamento
  - Historico
  - Controle de versão
  - Quem alterou
  - O quê alterou
  - Quando alterou
  - Todos os arquivos
  - Evolução continua

 Arquivo A | Versão 1 | Versão 2
 Arquivo B | Versão 1 | Versão 2

 ## Instalação do Git
https://git-scm.com/
 - windows: https://git-scm.com/download/win
 - Linux (apt-get): sudo apt-get install git
 - Mac (brew):brew install git
 
 ## Criar conta no GitHub

 ## Clonar o projeto

 ## Commits
 Informação de alteração
 - Após testado todo seu código
 - git add *
 - git commit -m'mensagem'
 - git push (enviar alterações para repositorio)
 - git pull (trazer alterações do GitHub para sua maquina)

 ## GitFlow
 Fluxo do Git

 ### Branchs
 são ramificações / versoes paraleras
 - main / master (vai para produção, quando o projeto é publicado)
 - develop
- DOD Definition of Done: Critérios de aceite
 - versionamento 1.0.0

 git checkout -b dev (cria uma branch)
 git checkout master (mudar de branch)

 ### Merge
 mescla de brachs
 você pode precisar resover conflitos manualmnte

 git merge main

 ### Pull Requests
 Mescla de branch no repositorio
 permite code review
 O repositorio resolve os conflitos automaticamente

 ## configurar o GitFlow
 git flot init 
 git floe feature start {nome-da-feature}
 