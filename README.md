# Atividade GitHub

Este repositorio possue os dados da atvidade que compreende criar um repositorio, clonalo no meu micro, criar um arquivo, commita-lo, criar um branch, alternar para ele editar o arquivo e commitar noavmente.
---

## Etapas Realizadas

1. **Criação e Clonagem do Repositório:**
   - Criei o repositório público `POO` na minha conta do GitHub.
   - Clonei o repositório no meu Ubuntu usando `git clone https://github.com/Joaogabriel0207/POO`.
  ![clone](Screenshot%20From%202026-11-02%2022-28-20.png)

2. **Edição na Branch Main:**
   - Entrei no diretório com `CD POO` e utilizei o `nano` para criar o arquivo `teste.java` contendo um código de Hello World.
   - Me identifique com email e senha usando `git config --global`.
   - O arquivo criado foi adicionado ao staging com `git add teste.java`, registradas localmente com `git commit -m "feat: adiciona o Hello World"` e enviadas ao GitHub com `git push origin main`.

![Screenshot 1](Screenshot%20From%202026-11-02%2023-23-46.png)

![Screenshot 2](Screenshot%20From%202026-11-02%2023-24-06.png)

![Nano](Screenshot%20From%202026-11-02%2022-32-06.png)


3. **Criação de um Ramo Alternativo (`Bye-World`):**
   - Criei e alternei para outro ramo chamado `Bye-World` usando o comando `git checkout -b Bye-World`.
   - Com o `nano` editei o `teste.java` para alterar a mensagem de saída de `Hello World` para `Bye Bye World`.
   - Registrei as modificaçoes com `git add` e `git commit`) e enviei o novo ramo ao repositório remoto com `git push origin Bye-World`.
