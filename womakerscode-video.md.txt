##  Git & Github: Do zero ao pull request

- [Link do vídeo](https://youtu.be/w4gx2qsjOP0)

### Anotações

- o Git controla um histórico de versões de um mesmo código atribuindo metadados referentes ao estado daquele código em determinado moomento que foi salvo por uma pessoa específica ("um commit é uma fotografia de um determinado estado do código");
- _branches_ são separações de código com as quais é possível que várias pessoas atuem num mesmo projeto, independentemente;
- toda vez que alteramos nosso projeto, além de salvar os arquivos, precisamos salvá-las no Git ("commitá-las");
- antes de fazer um _push_, a boa prática é fazer um _pull_;
- o _fork_ é bem parecido com o _clone_, porém só acontece na interface gráfica do GitHub, e é geralmente utilizado em projetos open source.

#### Fluxo básico para fazer um commit

```
//na branch criada anteriormente
git status
//verifica o que há de diferente na branch
git add .
//adiciona as mudanças encontradas pelo git status
git commit -m "mensagem da commit"
```

#### Inicializando um repositório

```
//crie uma nova pasta na sua máquina local
//abra essa pasta na sua IDE de preferência
git init
//pronto, já há um repositório rastreável pelo Git
```

#### Criando uma branch via terminal

```
//criando uma branch
git checkout -b minha-primeira-pr
//alternando entre branches
git checkout [nome da branch]
```