# Exercício de Casa :house:
## Utilizando as novas ferramentas
Claro, aqui está o passo a passo para criar um novo repositório no GitHub, cloná-lo na sua máquina, criar um arquivo JavaScript que imprime "Hello World", e então fazer commit e push dessas alterações para o GitHub:

1. **Crie um novo repositório no GitHub chamado hello-world**
    - Vá para o GitHub e faça login na sua conta.
    - Clique no botão `+` no canto superior direito e selecione `New repository`.
    - Nomeie o repositório como `hello-world` e clique em `Create repository`.

2. **Abra o terminal na sua máquina e navegue até a pasta que você criou durante as aulas**
    - Abra o terminal (ou prompt de comando).
    - Navegue até a pasta desejada usando o comando `cd`. Por exemplo, se a pasta se chama `estudos`, você digitaria `cd estudos`.

3. **Clone esse repositório na sua máquina**
    - No terminal, digite `git clone https://github.com/seu_nome_de_usuário/hello-world.git`, substituindo `seu_nome_de_usuário` pelo seu nome de usuário do GitHub.

4. **Crie um arquivo .js chamado hello-world.js**
    - Ainda no terminal, navegue para a pasta do repositório clonado com `cd hello-world`.
    - Digite `touch hello-world.js` para criar o arquivo.

5. **Imprima na tela a mensagem "Hello World"**
    - Abra o arquivo `hello-world.js` em um editor de texto.
    - Digite `console.log('Hello World');` e salve o arquivo.

6. **Execute esse arquivo através do terminal, utilizando o node**
    - No terminal, digite `node hello-world.js`. Você deverá ver a mensagem "Hello World" impressa na tela.

7. **Faça um commit para salvar esses arquivos na sua máquina**
    - No terminal, digite `git add .` para adicionar todas as alterações.
    - Em seguida, digite `git commit -m "Adicionado hello-world.js"` para fazer um commit das alterações.

8. **Dê push nesse commit e veja se essas alterações apareceram no seu GitHub**
    - No terminal, digite `git push origin master` para enviar as alterações para o GitHub.
    - Agora, se você for ao seu repositório `hello-world` no GitHub, deverá ver o arquivo `hello-world.js`.

