### Para que eu mostrar como fazer uma resolução de conflito, preciso causar ele MUA HAHA!

### Para trazer uma noção melhor de onde começamos, o print abaixo mostra como o arquivo “resolucao_conflito.md” estava antes do conflito:

![Texto alternativo](ImagensConflito/Imagem1.png)


### Com isso, podemos acessar o github, fazer alguma alteração e um commit

![Texto alternativo](ImagensConflito/Imagem2.png)

### Após isso, vamos para o vscode fazer outra alteração e salvá-la. Agora, para o conflito em si ocorrer, vamos fazer uma requisição de git pull, que vai resultar em um erro informando que irá acontecer uma sobreescrita das minhas alterações locais.

![Texto alternativo](ImagensConflito/Imagem3.png)


### Então vamos utilizar um git stash para armazenar nossas alterações locais e para que a gente consiga trazer as alterações do github

![Texto alternativo](ImagensConflito/Imagem4.png)

### E mais um git pull, com o objetivo de puxar como estão os arquivos no github:

![Texto alternativo](ImagensConflito/Imagem5.png)

### Agora vamos precisar fazer uma escolha, de qual versão manter, a do stash (feita localmente) ou a pelo que foi trazida pelo github. Para isso, utilize um git stash apply 0, para pegar o stash da posição 0:

![Texto alternativo](ImagensConflito/Imagem6.png)

### Clicando em “Resolver no Editor de Mesclagem”, vamos conseguir escolher a versão final:

![Texto alternativo](ImagensConflito/Imagem7.png)

### Se a “Mudanças em Stash” for selecionada, é preciso fazer um commit para que as mudanças sejam enviadas para o servidor. Enquanto que, se eu escolher a “Atual” eu não preciso fazer commit, por conta deste ter sido “puxado” do servidor.
