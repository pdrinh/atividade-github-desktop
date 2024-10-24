# Atividade Prática: Aprendendo Git e GitHub com GitHub Desktop

Bem-vindo(a) à atividade prática para aprender a usar o Git e o GitHub com o **GitHub Desktop**! Durante esta atividade, você irá explorar conceitos fundamentais como **branches**, **commits**, **checkouts**, **merges** e **pull requests** (PRs). O objetivo é proporcionar uma experiência prática de como o versionamento de código funciona em um ambiente colaborativo.

## Pré-requisitos

- Certifique-se de ter uma conta no GitHub.
- Baixe e instale o [GitHub Desktop](https://desktop.github.com/).
- Configure o GitHub Desktop com sua conta do GitHub.

## Configuração do Repositório

### 1. Clonar o Repositório Compartilhado

1. Obtenha a URL do repositório compartilhado (fornecida pelo instrutor).
2. Abra o **GitHub Desktop**.
3. Clique em `File` > `Clone Repository...`.
4. Na aba `URL`, cole a URL do repositório compartilhado e selecione o local onde deseja salvar o projeto no seu computador. Clique em `Clone`.

## Tarefas para Realizar

Abaixo estão as etapas que você deve seguir para completar esta atividade. Siga as instruções e explore o máximo que puder!

### 2. Criar uma Nova Branch

1. No GitHub Desktop, certifique-se de que o repositório correto está selecionado.
2. No canto superior esquerdo, clique no menu suspenso ao lado do nome da branch e selecione `New Branch...`.
3. Nomeie sua nova branch utilizando sua turma e seu nome (por exemplo, `PJD4V-luiz-paulo-branch`) e clique em `Create Branch`.
4. Certifique-se de que está na sua nova branch (você verá o nome dela no topo).

### 3. Fazer Modificações e Realizar Commits

1. Abra o arquivo `estudantes`, dentro da pasta com o nome da sua turma, em um editor de texto e adicione uma linha com seu nome completo (caso já haja algum outro nome no arquivo, certifique-se que seu nome foi adicionado respeitando a ordem alfabética).
2. Volte ao **GitHub Desktop**. Você verá as mudanças listadas na aba `Changes`.
3. Digite uma mensagem de commit que descreva suas alterações e clique em `Commit to [nome da branch]`.

### 4. Sincronizar as Mudanças com o Repositório Remoto

1. Depois de realizar um commit, clique no botão `Push origin` no **GitHub Desktop** para enviar suas mudanças para o GitHub.

### 5. Criar um Pull Request (PR)

1. No **GitHub Desktop**, após o push, clique no botão `Create Pull Request` que aparecerá na interface, ou:
2. No navegador, acesse o repositório compartilhado e clique na aba **"Pull Requests"**.
3. Clique em **"New pull request"**.
4. Escolha sua branch na lista e compare-a com a branch principal (`main`).
5. Descreva suas mudanças e clique em **"Create pull request"**.
6. Aguarde o feedback e aprovação do mantenedor do projeto.

### 6. Sincronizar o Código Atualizado do Repositório Principal

1. Para manter seu repositório local atualizado com o repositório principal, clique em **"Fetch origin"** no GitHub Desktop.
2. Se houver atualizações na branch `main`, você pode mesclá-las na sua branch de trabalho:
   - Clique em `Branch` > `Merge into current branch...`.
   - Selecione a branch `main` para mesclar as mudanças.

## Recursos Úteis

- [Documentação do GitHub Desktop](https://docs.github.com/en/desktop)
- [Guia do GitHub](https://guides.github.com/activities/hello-world/)
- [Tutorial Interativo de Git](https://learngitbranching.js.org/)

Bom trabalho e boa sorte! 🚀
