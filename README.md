# Guia de GIT e GitHub

Este repositório foi criado para explicar as principais funções do GIT e GitHub, também contém os passos necessários para postar um projeto online.

---

## Quais são as principais funções disponíveis no GIT?

O GIT é um sistema de controle de versão distribuído, usado para gerenciar o histórico de alterações de arquivos em projetos. Suas principais funções incluem:

- **Rastreamento de versões:** Permite salvar o histórico de alterações.
- **Trabalho colaborativo:** Ele tem o suporte para que múltiplos desenvolvedores possam trabalhar simultaneamente.
- **Branching:** Criação de ramificações para desenvolvimento paralelo.
- **Rollback:** Ele apresenta a opção de retornar para versões anteriores em caso de erro.

---

## Principais Funções do GitHub

O GitHub é uma plataforma baseada na web para hospedagem e gerenciamento de repositórios GIT. 

Seus principais recursos são:

- **Hospedagem de código:** Armazena e compartilha repositórios.
- **Colaboração:** Ele permite que múltiplos usuários contribuam no projeto com ferramentas como Pull Requests.
- **Automação:** Integrações com CI/CD e outros serviços.
- **Documentação:** Fornece ferramentas para criar wikis e documentações.

---

## Principais Comandos do GIT para utilizar em seus projetos:

- **`git init`:** Inicializa um repositório GIT.
- **`git add`:** Adiciona arquivos ao staging.
- **`git commit`:** Salva alterações com uma mensagem.
- **`git push`:** Envia alterações para o repositório remoto.
- **`git pull`:** Baixa alterações do repositório remoto.
- **`git clone`:** Clona um repositório remoto.

---

## Como criar um repositório no GitHub?

- Para isso basta acessar seu perfil e ir na aba "repositório" ou "Repositories" na versão inglês. 
- Depois disso clique no botão "novo" ou "New" na versão inglês.
- Digite um nome para o seu repositório na aba "Nome do repositório" ou "Repository name*".
- Coloque uma descrição se achar necessário e deixe a opção do repositório como "público" ou marque a opção "privado" se quiser que apenas você tenha acesso aos projetos.
- Marque a opção (Add a README file) e finalize clicando na opção Criar Repositório ou "Create Repository".

Pronto, seu repositório foi criado e agora vem a parte mais importante que é fazer os primeiros posts no seu repositório. 

**Veja os próximos passos abaixo:**

## Como Postar um Projeto salvo no armazenamento local no GitHub?

Os primeiros passos 

1. **Inicializar o GIT no projeto:**

Utilizando o **Prompt de Comando** ou **terminal do Vscode** você deve digitar o comando abaixo:

 `git init`

lembrando que você deve abrir o diretório onde seu projeto está salvo localmente para começar a postar.

2. **Adicionar os arquivos ao repositório:**

`git add .`

3. **Criar o primeiro commit:**

`git commit -m "Primeiro commit"`

4. **criar o arquivo main**

`git branch -M main`

O comando `git branch -M main` é frequentemente usado para renomear a branch padrão (geralmente chamada de master) para main, pois muitos projetos atualmente adotam main como padrão.

5. **Conectar o repositório local ao GitHub:**

`git remote add origin <URL do seu repositório do GitHub>`

6. **Enviar os arquivos para o GitHub:**

`git push -u origin main`

Pronto, agora basta verificar se todos os arquivos foram postados corretamente no seu repositório do GitHub.



