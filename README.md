# Laboratório: Treinando Git no Azure DevOps

## Objetivo
Praticar conceitos de Git, como criação de commits, pull requests, criação de branches, e explorar os modelos trunk-based e tradicional, utilizando repositórios no Azure DevOps.

---

## Exercícios

### 1. Configuração Inicial do Repositório
- **Descrição**: 
  - Crie um repositório no Azure DevOps chamado `git-lab-devops`.
  - Clone o repositório para o seu ambiente local.
  - Confirme que o repositório está vazio.
  - Configure as credenciais locais para autenticação com o Azure DevOps.

---

### 2. Criação de Branches e Commit
- **Descrição**: 
  - No repositório local:
    - Crie uma branch chamada `feature/add-readme`.
    - Na nova branch, crie um arquivo `README.md` e adicione as informações do projeto (nome e objetivo fictício do repositório).
    - Adicione e comite o arquivo na branch `feature/add-readme`.
    - Envie a branch para o repositório remoto.

---

### 3. Criação e Revisão de Pull Request
- **Descrição**: 
  - No Azure DevOps:
    - Crie um Pull Request (PR) para mesclar a branch `feature/add-readme` na branch `main`.
    - Adicione uma descrição ao PR, explicando as alterações realizadas.
    - Marque a revisão como necessária para aprovação (pode ser fictício ou autorrevisado).
    - Após a aprovação, conclua o PR e exclua a branch `feature/add-readme`.

---

### 4. Prática de Modelos (Trunk-Based vs. Tradicional)
- **Descrição**:
  - **Trunk-Based**:
    - Na branch `main`, adicione diretamente uma seção "Descrição do Projeto" no arquivo `README.md`.
    - Comite e envie a alteração diretamente na branch `main`.
  - **Tradicional**:
    - Crie uma nova branch chamada `feature/add-contribution-guide` a partir da branch `main`.
    - Adicione uma seção ao `README.md` chamada "Guia de Contribuição".
    - Realize o commit e envie a branch para o repositório remoto.
    - Crie um PR para revisar e mesclar na branch `main`.

---

## Entrega
- Documente cada etapa realizada em um arquivo `LAB.md` no repositório, explicando o que foi feito em cada exercício.
- Certifique-se de que todas as branches estejam organizadas e os PRs aprovados ou concluídos.

---
