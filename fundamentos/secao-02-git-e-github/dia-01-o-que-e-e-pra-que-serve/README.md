# DIA 3

O objetivo do dia foi criar um repositório local e algumas branches com o git

Os requisitos do exercício são:

1. Crie uma pasta no seu computador;
2. Acesse a pasta que você acabou de criar;
3. Inicie o versionamento com o comando `git init`;
4. Abra a pasta no *VSCode* com o comando `code .`;
5. Crie um arquivo chamado `README.md`;
6. Adicione o arquivo novo em *staging* e realize um `commit`. Por exemplo: `git add .` e `git commit -m "Descreva a alteração realizada"`;
7. Crie uma nova `branch` com o comando `git checkout -b`. Por exemplo: `git checkout -b adiciona-readme`;
8. Faça uma alteração no README.md e retorne para a `branch main`, em seguida realize o `merge` das alterações com o comando `git merge nome-da-branch`. Por exemplo: `git merge adiciona-readme`.

Agora que você já criou a pasta e mergeou as alterações, vamos avançar e criar novas `branches`!

- Acesse a `branch main` e crie uma `branch` nova chamada `atualiza-readme`;
- Acesse a `branch atualiza-readme` e crie um arquivo chamado `infos.txt`;
- Adicione as alterações em *staging* e realize um `commit`;
- Adicione seu nome e sobrenome no arquivo `infos.txt`;
- Adicione novamente as alterações em *staging* e realize um `commit`;
- Crie uma `branch` nova a partir da `branch atualiza-readme`. A nova `branch` deve se chamar `adiciona-infos`;
- Acesse a `branch adiciona-infos` e utilize sua criatividade para escrever o passo a passo de como o versionamento funciona no `README.md`. Por exemplo: “O primeiro passo é ter uma pasta versionada e criar um estrutura inicial e fazemos isso utilizando o comando `git init`. O segundo passo é criar uma branch nova com o comando `git checkout nome-da-branch` ou `git checkout -b nome-da-branch`“, etc. Você também pode utilizar esse momento para escrever e responder as dúvidas que voc6e ainda tem sobre versionamento.
- Adicione as alterações em *staging*, realize o `commit`;
- Volte para a `branch atualiza-readme` e realize o `merge` das alterações feitas na `branch adiciona-infos`;
- Retorne para a `branch main` e realize o `merge` das alterações.
