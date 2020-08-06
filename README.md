# Git: Aprendendo na prática

[Meetup](https://www.meetup.com/opensanca/events/272092986/)

```
          o-o-o (branch-1)
         /     \
o-o-o-o-o-o-o-o-o-o-o (main)
         \         /
          o-o-o-o-o (branch-2)
```


A ideia deste curso é auxiliar o aprendizado de git seguindo três etapas:
- motivação : Por que aprender algo
- teoria    : O que é isso
- prática   : Como usar + exercícios de fixação

O curso tem como intenção exigir o mínimo de outras tecnologias que não o próprio git. Dessa forma, evita-se 
qualquer linguagem de programação específica e são utilizados arquivos de texto .md para teoria e práticas.

Alguns comandos ou argumentos que facilitam o trabalho do dia a dia serão intencionalmente ignorados a fim 
de apresentar boas práticas no uso da ferramenta git.

# Organização do curso

O curso está organizado nas seguintes partes e seções:

## Parte 1: Aula Expositiva

Durante essa parte, um palestrante falará sobre cada uma das seguintes seções
e ao mesmo tempo mostra em um terminal sobre o que está falando. Aconselha-se
a quem está assistindo ao curso que acompanhe conforme conseguir o conteúdo apresentado.

## Parte 2: Prática

Durante essa parte, o palestrante e possivelmente outros instrutores auxiliarão
na execução das tarefas listadas.

# Índice

## 1. Aula

1. [O que é o git e por que eu deveria me importar?](motivacao.md)
    - As duas ferramentas mais importantes
    - Sistema de controle de versões (vcs)
    - O dia a dia
    - Comandos
      - `git help`

1. [Visão geral do git](visao-geral.md)

1. [Configurando o git](configurando-o-git.md)
    - Configurações Globais
    - Configurações Locais

1. [Diretório de trabalho](diretorio-de-trabalho.md)

1. [O repositório git](repositorio.md)
    - Iniciando um repositório
    - Checando o resporitório
    - O diretório git
    - Comandos
      - `git init`
      - `git status`

1. [Preparando o **stage**](stage.md)
    - O que é o **stage**?
    - O que é uma modificação?
      - Arquivos
      - Chunks
    - Comandos
      - `git add`
      - `git reset`
      - `git diff`
    
1. [A base de tudo, o **commit**](commit.md)
    - O que é um **commit**?
    - Comandos
      - `git commit`
      - `git log`
    - Boas práticas ao criar um **commit**
    
1. [Dividir para conquistar!](branch.md)
    - O que é um **ref**?
    - O que é um **branch**?
    - O que é uma **tag**?
    - O que é o **HEAD**?
    - Comandos
      - `git branch`
      - `git tag`
      - `git checkout`

1. [Juntando o trabalho](merge-rebase.md) 
    - O que é um **merge**?
    - O que é um **rebase**?
    - Comandos
      - `git merge`
      - `git rebase`
    - O que é um conflito?
    - Resolvendo conflitos
    
1. [Local e remotes](local-remote.md)
    - O que é o **local**?
    - O que é um **remote**?
    - Comandos:
      - `git clone`
      - `git remote`
      - `git fetch`
      - `git push`
      - `git pull`
    
1. [Saiba mais](saber-mais.md)
    - Padrões de commit
      - Convertional commits
    - Nomeando versões
      - Semantic versioning
    - Quem foi que fez isso?!?
      - `git blame`
    - O que é o **reflog**?
      - `git reflog`
    - O que é o **stash**?
      - `git stash`
      - `git stash pop`
    - O que é **cherry-pick**?
      - `git cherry-pick`
    - O que é **bisect**?
      - `git bisect`
    - O que são **hooks**?
    
1. [Fluxos de trabalho para git](fluxos.md)

## 2. Prática

1. [Exercício 1](exercicio-1.md)

