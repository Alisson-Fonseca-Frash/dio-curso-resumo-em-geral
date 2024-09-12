# DIO | NTT DATA - Engenharia de dados com Python

Repositório para armazenar resumos sobre o curso NTT DATA - Engenharia de dados com Python [DIO](https://web.dio.me/track/engenharia-dados-python)🔗

## 📒📋Documentação Git e Github
  - [Documentação Git](https://git-scm.com/doc)🔗
  - [Documentação Github](https://docs.github.com/)🔗


  
```
git init adiciona raiz no diretório (main) e para remover a raiz, usa-se o comando:  rm -rf .git 
git add . (para criar um novo commit)
git log (para ver os commit's ativos e alterados) 
mkdir usa-se para criar um novo diretório
```
Exemplos de comandos acima:

exemplo de remover [git init](https://drive.google.com/file/d/19YkOPY9XEUErLSzX7UwqvqcuU0TfJLPD/view?usp=sharing)🔗

## 🔍 Referências

- [Digital Innovation One](https://dio.me)🔗


## 📚 Aprendizados

O que você aprendeu construindo esse projeto? Quais desafios você enfrentou e como você superou-os?

## 💻 Resumos das aulas

  |Aulas | Resumos |
  |------|---------|
  | Salvando Alterações no Repositório Local | _".gitkeep" para pastas vazias serem exibidas no git. E ".gitignore" para ignorar um diretório ou pasta._ |
| Desfazendo alterações no repositório local | _O comando "rm -rf .git" serve para apagar um "git init" que foi aplicado a algum repositório. "git restore" usado para restaurar alterações indevidas. "git commit --amend -m"Texto"." para trocar a msg do commit. Ou o código "git commit --ammend" para abrir o editor de commit. Que para escrever aperta a tecla "i", e para sair aperta a tecla "esc" depois dois pontos ":" para escrever "wq" e dar enter. Já para dar um reset no commit, usa-se "git reset". Temos três opções: soft,mixed ou hard_.
| | Para "soft", Copia o codigo Commit [(Exemplo)](https://drive.google.com/file/d/1WTIC8Mrga2nsA3I_0rAIC6r01FdY3hGI/view?usp=sharing)🔗, e comando: git reset --soft (cola o codigo Commit).|
|| Para "mixed", Copia o código Commit [(Exemplo (Porém troca a opção "soft" para "mixed"))](https://drive.google.com/file/d/1WTIC8Mrga2nsA3I_0rAIC6r01FdY3hGI/view?usp=sharing)🔗, e comando: git reset --mixed (cola o código Commit).|
|| Para "hard", Copia o código Commit [(Exemplo (Porém troca a opção "soft" para "hard"))](https://drive.google.com/file/d/1WTIC8Mrga2nsA3I_0rAIC6r01FdY3hGI/view?usp=sharing)🔗, e comando: git reset --hard (cola o código Commit).


## **Relacionados a git reset**

## Sobre **_git reset_**

O comando `git reset` é usado para redefinir o estado do repositório Git para um commit anterior. Existem três modos principais de `git reset`: `--soft`, `--mixed` e `--hard`. Aqui estão as diferenças entre eles:

1. **`git reset --soft:`**
   - **HEAD**: Move o ponteiro _HEAD_ para o commit especificado.
   - **Índice (staging area)**: Não é alterado.
   - **Diretório de trabalho**: Não é alterado.
   - **Uso**: As mudanças permanecem no índice, prontas para serem commitadas novamente.
   
2. **`git reset --mixed`** _(padrão)_:
   - **HEAD:** Move o ponteiro _HEAD_ para o commit especificado.
   - **Índice (staging area):** É redefinido para coincidir com o commit especificado.
   - **Diretório de trabalho:** Não é alterado.
   - **Uso:** As mudanças são removidas do índice, mas permanecem no diretório de trabalho, permitindo que você as revise ou modifique antes de adicionar novamente ao índice.

3. **`git reset --hard:`**
   - **HEAD**: Move o ponteiro _HEAD_ para o commit especificado.
   - **Índice (staging area)**: É redefinido para coincidir com o commit especificado.
   - **Diretório de trabalho**: É redefinido para coincidir com o commit especificado.
   - **Uso**: Todas as mudanças no índice e no diretório de trabalho são descartadas, retornando o repositório ao estado do commit especificado¹².


         Esses comandos são poderosos e devem ser usados com cuidado, especialmente o `--hard`, pois ele pode resultar na perda de mudanças não commitadas.


Fontes: 19/08/2024

¹ [Git - git-reset Documentation.](https://git-scm.com/docs/git-reset)🔗

² [Git Reset | Hard, Soft & Mixed | Learn Git - GitKraken.](https://www.gitkraken.com/learn/git/git-reset)🔗

[(1) Git - git-reset Documentation.](https://git-scm.com/docs/git-reset)🔗

[(2) Git Reset | Hard, Soft & Mixed | Learn Git - GitKraken. ](https://www.gitkraken.com/learn/git/git-reset)🔗

[(3) What’s The Difference Between git reset –mixed, –soft, and –hard?. ](https://bing.com/search?q=git+reset+soft+mixed+hard)🔗
[(4) 程序员 - 掌握 Git Reset 三大模式：Soft、Mixed 和 Hard 的实战指南 - 个人文章 - SegmentFault 思否. ](https://segmentfault.com/a/1190000044719020)🔗

[(5) What’s The Difference Between git reset –mixed, –soft, and –hard? ](https://www.geeksforgeeks.org/whats-the-difference-between-git-reset-mixed-soft-and-hard/)🔗
## **Enviando e Baixando alterações com o Repositório Remoto**

```
git add . (Serve para adicionar tudo do diretório)
git push  é responsável por enviar alterações do Repositório local para o Repositório Remoto.
(Código: git push -u (sendo que o -u é uma abreviação pra --set -upstream. Ele configura o branch remoto como o upstream para o branch local, facilitando futuras operações de push e pull sem a necessidade de especificar o branch remoto novamente.))

```


#  **Versionamento de Código com Git e GitHub**

## Ferramentas

[![Git](https://img.shields.io/badge/Git-000?style=for-the-badge&logo=git&logoColor=E94D5F)](https://git-scm.com/doc) 
[![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=30A3DC)](https://docs.github.com/)
<br>

## Objetivo
Introduzir ao versionamento de código com Git e GitHub.


## Percurso
<table>
  <thead>
    <tr align="left">
      <th>Nº</th>
      <th>Etapas</th>
      <th>Materiais de Apoio</th>
    </tr>
  </thead>
  <tbody align="left">
    <tr>
      <td>01</td>
      <td>Visão Geral do Curso e Ferramentas</td>
      <td align="center">
        <a href="https://github.com/elidianaandrade/dio-curso-git-github/blob/main/materiais-de-apoio/01-visao-geral-do-curso-e-ferramentas.md">
           <img align="center" alt="Material de Apoio" src="https://img.shields.io/badge/Ver%20Material-30A3DC?style=for-the-badge">
        </a>
      </td>
    </tr>
    <tr>
      <td>02</td>
      <td>Instalação, Configuração e Autenticação</td>
      <td align="center">
        <a href="https://github.com/elidianaandrade/dio-curso-git-github/blob/main/materiais-de-apoio/02-instalacao-configuracao-e-autenticacao.md">
           <img align="center" alt="Material de Apoio" src="https://img.shields.io/badge/Ver%20Material-E94D5F?style=for-the-badge">
        </a>
      </td>
    </tr>
    <tr>
      <td>03</td>
      <td>Primeiros Passos com Git e GitHub</td>
      <td align="center">
        <a href="https://github.com/elidianaandrade/dio-curso-git-github/blob/main/materiais-de-apoio/03-primeiros-passos-com-git-e-github.md">
           <img align="center" alt="Material de Apoio" src="https://img.shields.io/badge/Ver%20Material-30A3DC?style=for-the-badge">
        </a>
      </td>    
    </tr>
    <tr>
      <td>04</td>
      <td>Dicas e Materiais de Apoio</td>
      <td align="center">
        <a href="https://github.com/elidianaandrade/dio-curso-git-github/blob/main/materiais-de-apoio/04-dicas-e-materiais-de-apoio.md">
           <img align="center" alt="Material de Apoio" src="https://img.shields.io/badge/Ver%20Material-E94D5F?style=for-the-badge">
        </a>
      </td>    
    </tr>
  </tbody>
  <tfoot></tfoot>
</table>

## Referências
- [GIT. Documentation](https://git-scm.com/doc)
- [GITHUB. Documentation](https://docs.github.com/)
- [GITHUB BLOG. February 28th DDoS Incident Report](https://github.blog/2018-03-01-ddos-incident-report/)
- [GITHUB BLOG. February 28th DDoS Incident Report](https://github.blog/2018-03-01-ddos-incident-report/)
- [GITHUB BLOG. Raising the bar for software security: GitHub 2FA begins March 13](https://github.blog/2023-03-09-raising-the-bar-for-software-security-github-2fa-begins-march-13/)
- [GITHUB BLOG. Token authentication requirements for Git operations](https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/)
- [MICROSOFT. Microsoft to acquire GitHub for $7.5 billion](https:/news.microsoft.com/2018/06/04/microsoft-to-acquire-github-for-7-5-billion/)

# Trabalhando com Branches - Comandos Úteis no Dia a Dia

* Conflito de merge - quando usamos o comando `git pull`, nada mais é qe a junção do comando `git fetch` (que baixa as alterações) + `git merge` (que mescla as alterações).

Para baixar do repositório remoto, sem mesclar no local usamos o comando `git fetch` [(exemplo: git fetch origin main (repositório origin e Branch main)).](https://drive.google.com/file/d/11mwl8ofGx3fqiY9jfyFFagS6XzjQ7n1G/view?usp=sharing)🔗

* **Comando `git diff`:**

O comando git diff é utilizado para comparar as diferenças entre diferentes estados do repositório Git. Ele pode ser usado para visualizar as alterações entre:

O diretório de trabalho e o índice (staging area).
O diretório de trabalho e o último commit.
Dois commits específicos12.
Por exemplo, se você fez modificações em alguns arquivos e quer ver o que mudou antes de fazer um commit, você pode usar git diff para ver essas alterações. Aqui está um exemplo básico:

    git diff

Isso mostrará todas as mudanças que você fez no seu código que ainda não foram adicionadas ao índice. Se você já adicionou as mudanças ao índice e quer ver o que será incluído no próximo commit, você pode usar:

    git diff --cached

* Depois de ter utilizado o comando `git fetch`, utilizamos o comando `git merge` [(exemplo: git merge origin/main)](https://drive.google.com/file/d/16TdR43MoKq7ds0qz6K308UiEWb9SfNVk/view?usp=sharing)🔗
[exemplo de `git merge origin/main` no repositório local](https://drive.google.com/file/d/1sMq4sokct6yTtt2GO9qF9tZ3cIluogXF/view?usp=sharing)🔗

### Clonando um repositório que tenha várias Branches, mas só precisa de uma delas

Para clonar um repositório Git e trazer apenas uma branch específica, você pode usar o comando git clone com algumas opções adicionais. Aqui está como fazer isso:

    git clone -b <nome-da-branch> --single-branch <url-do-repositorio>

Substitua <nome-da-branch> pelo nome da branch que você deseja clonar e <url-do-repositorio> pela URL do repositório.

Por exemplo, se você quiser clonar apenas a branch develop de um repositório, o comando seria:

    git clone -b develop --single-branch https://github.com/usuario/repositorio.git

Isso garante que apenas a branch develop seja clonada, economizando tempo e espaço.

Exemplo de [clone remoto ](https://drive.google.com/file/d/1PVGW91yTFS1EfZXfV0f5JY9Sv-ayi8wY/view?usp=sharing)🔗

Para visualizar, [usamos o comando `cd repo-remoto`](https://drive.google.com/file/d/1VfsdSrh9YFJNKjxg8gJg8zDp33dVuYD4/view?usp=sharing)🔗

* Comando para arquivar atualização que foi feita [`git stash`](https://drive.google.com/file/d/1kMQUUuZfovHS2SEiWP5Dqo-yRIIcEsGM/view?usp=sharing)🔗
* Comando para listar as atualizações que fora arquivado [`git stash list`](https://drive.google.com/file/d/10l2plgocT7aocOoK6UY9ZbZq7-ACgROo/view?usp=sharing)🔗

* git stash pop 

O comando `git stash pop` é usado para aplicar as mudanças salvas no stash mais recente e, em seguida, remover essa entrada do stash. Basicamente, ele recupera as alterações que você salvou temporariamente e as aplica à sua branch atual.

Aqui está um exemplo de como usar:

```bash
git stash pop
```

Se você tiver várias entradas no stash e quiser aplicar uma específica, você pode usar:

```bash
git stash pop stash@{n}
```

Substitua `n` pelo índice da entrada do stash que você deseja aplicar.

* Comando `git stash apply`

O comando `git stash apply` é usado para aplicar as mudanças salvas no stash à sua branch atual, mas, ao contrário de `git stash pop`, ele não remove a entrada do stash após aplicá-la. Isso pode ser útil se você quiser aplicar as mesmas mudanças em várias branches ou se quiser manter o stash como backup.

Aqui está como usar:

```bash
git stash apply
```

Se você tiver várias entradas no stash e quiser aplicar uma específica, você pode usar:

```bash
git stash apply stash@{n}
```

Substitua `n` pelo índice da entrada do stash que você deseja aplicar.
## **Tipos de dados no Python**

## _Percurso_

 ## `Etapa 1:`
 
    O que são os tipos? 
      Os tipos servem para definir as características e comportamentos de um valor (objeto) para o interpretador.
      Por exemplo:
      
      Com esse tipo eu sou capaz de realizar operações matemáticas. Esse tipo para ser armazenado em memória irá consumir 24 bytes.

## Tipos em Python

  __Os tipos built-in são:__

|__Tipos__ | __Códigos__|
|------|-----|
| Texto | str |
| Númerico| int, float, complex |
|Sequência | list, tuple, range |
|Mapa | dict |
|Coleção | set, fronzenset |
| Booleano | bool |
| Binário | bytes, bytearray, memoryview |


 ## `Etapa 2:` 
 
    Tipos númericos

Números inteiros são representados pela classe *int* e possuem precisão ilimitada. São exemplos de números inteiros:

    1, 10, 100, -1, -10, -100... 940012235
    
 `Números de ponto flutuante`

Os números de `ponto flutuante` são usados para representar os números racionais e sua implementação é feita pela classe `float`. São exemplos válidos de números de ponto flutuante:

    1.5, -10.323, 0.32.... 8999320.023

 ## `Etapa 3:`
    
    Booleanos e Strings

   * ## `Booleano:`

É usado para representar verdadeiro ou falso, e é implementado pelo classe _`bool`_. Em  _Python_ o tipo Booleano é uma subclasse de *`int`*, uma vez que qualquer número diferente de 0 representa _verdadeiro ou falso_. São exemplos válidos de Booleanos:

    True e False

* ## `Strings`

Strings ou `cadeia de caracteres` são usadas para representar valores alfanúmericos, em Python as strings são definidas utilizando a classe `str`. São exemplos válidos de string:

    "Python", 'Python', """Python""", '''Python''' , "p"


|  💭 Lembrando que números não se somam com letras numa string, por exemplo: print(açucar + 3,50) |
|-------|


## Modo interativo Python

# 📒 Objetivo geral

Como usar o modo interativo do interpretador Python.

## __Percurso__

### * Etapa 1
__Usando o modo interativo:__

O interatador Python pode executar em modo que possibilite o desenvolvedor a escrever código, e ver o resultado na hora.

| _Existem duas formas de iniciar o modo interativo, chamando apenas o interpretador (python) ou executando o script com a flag -i (python -i app.py)._ |
|----|

Exemplo [python](https://drive.google.com/file/d/156Ojlj54WjPnqkexosK_7lOeRQA8EY3S/view?usp=sharing)🔗

Exemplo [python -i](https://drive.google.com/file/d/10iaI47adLap8Wv78rkg8V4IguibzbD3n/view?usp=sharing)🔗

 ### * Etapa 2

__Funções dir e help:__

* __dir__
_Sem argumentos, retorna a lista de nomes no escopo local atual. Com um argumento, retorna uma lista de atributos válidos para o objetivo.
exemplo:_

`dir()`

`dir(100)`

Exemplo: [Clique aqui](https://drive.google.com/file/d/1LhxPaXiGozbtOi1hGzh7WJaIMfL-ton3/view?usp=sharing)🔗

Exemplo de dir() "int" : [Clique aqui](https://drive.google.com/file/d/1okJ5NPhBIEfN4htyNkqDRGgWeykv_nSK/view?usp=sharing)🔗


* __help__

_Invoca o sistema de ajuda integrado. É possível fazer buscas em modo interativo ou informar por parâmentro qual o nome do `módulo, função, classe, método ou variável`. Exemplo:_

`help()`

Exemplo: [Clique aqui](https://drive.google.com/file/d/1eUWWq8eEkZOEXpaiebX8bDSix0wr4mdH/view?usp=sharing)🔗


`help(100)`


Exemplo: [Clique aqui](https://drive.google.com/file/d/1VPMdg46HIipl7y4ljSDOcrneX_-B-vwW/view?usp=sharing)🔗

    Para sair da documentação apertar a letra "q".


# Links úteis:

* Gui Carvalho: [trilha python dio](https://github.com/guicarvalho/trilha-python-dio)🔗
* Referências: [Modo interativo](https://wiki.python.org.br/ModoInterativo)🔗
# Variáveis e Constantes

## Variáveis

_Em linguagens de programação podemos definir valores que podem sofre alterações no decorrer da execução do programa. Esses valores recebem o nome de Variáveis, pois eles nascem com um valor e não necessariamente devem permanecer com o mesmo durante a execuçãodo programa._

Exemplo de [variáveis](https://drive.google.com/file/d/19GaeZFVpK__Sw7-tl4iOnurauQZE05tD/view?usp=sharing)🔗

No Python, podemos usar várias variáveis em apenas uma linha, separando tudo por virgulas.



## Alterando os valores

_Perceba que não precisamos definir o tipo de dados da variável, o Python faz isso automaticamente para nós. Por isso não podemos simplesmente criar uma variável sem atribuir um valor. Para alterar o valor da variável basta fazer uma atribuição de um novo valor:_

Exemplo 1: [Clique aqui](https://drive.google.com/file/d/19GaeZFVpK__Sw7-tl4iOnurauQZE05tD/view?usp=sharing)🔗

Exemplo 2: [Clique aqui](https://drive.google.com/file/d/1A_lErVAvirvs9Uu_AsJ3dIad3TjRQUIk/view?usp=sharing)🔗

## Constantes

_Assim como as variáveis, constantes são utilizadas para armazenar valores. Uma constante nasce com um valor e permanece com ele até o final da execução do programa, ou seja, o valor é imutável._

Exemplo 1: [Clique aqui](https://drive.google.com/file/d/19GaeZFVpK__Sw7-tl4iOnurauQZE05tD/view?usp=sharing)🔗

Exemplo 2: [Clique aqui](https://drive.google.com/file/d/1A_lErVAvirvs9Uu_AsJ3dIad3TjRQUIk/view?usp=sharing)🔗


# Python não tem constantes

_Não existe uma palavra reservada para informar ao interpretador que o valor é constante. Em algumas linguagens por exemplo: `Java` e `C` utilizamos `final` e `const`, respectivamente para declarar uma constante.

Em Python usamos a convenção que diz ao programador que a variável é uma constante. Para fazer isso, você deve criar a variável com o nome todo em letras maiúsculas:

Exemplo: [Clique aqui]( https://drive.google.com/file/d/1qJI34fX_w-DO0qbqnSRFj9VR8zUrt20_/view?usp=sharing )🔗


# Boas práticas

// Seguindo as convenções

* O padrão de nomes deve ser snake case.

      Os espaços em brancos são preenchidos por underline ( _ ) Exemplo: *(valor_total)*

* Escolher nomes sugestivos.

      Ex: Limite diário saque 4. (limite_diario_4)

* Nome de constantes todo em maiúsculo.

      Ex: states = ['SP', 'RJ', 'SE']

# Conversão de tipos

_Aprender a converter os tipos das variáveis._

## Convertendo tipos

Em alguns momentos é necessário converter o tipo de uma variável para manipular de forma diferente. por exemplo:

|Variáveis do tipo *string*, que  armazenam números e precisamos fazer alguma operação matemática com esse valor.|
|---|

Exemplo de [inteiro para float](https://drive.google.com/file/d/19A26UUo15hJtkza1KhC0EqnxK4Xyk8wR/view?usp=sharing)🔗

Exemplo de [float para inteiro](https://drive.google.com/file/d/1zj9vq4ihAEScqCYw0j-3AgJo5VjV6aV4/view?usp=sharing)🔗 

Exemplo de [Númerico para string](https://drive.google.com/file/d/1cYTjlmb--bHRJ1U7rbAxtgSIfaP4Q3ms/view?usp=sharing)🔗

Exemplo de [string para Númerico](https://drive.google.com/file/d/1W_yt9hLpysbAfo9i_RKE2pVNYlDzJi7o/view?usp=sharing)🔗

Exemplo de [Erro de Conversão](https://drive.google.com/file/d/1nS5c1P8FUD2x6eNdTMw2hiPpKJ_3sY3i/view?usp=sharing)🔗

Exemplo de [Conversão de tipos e todos no geral](https://drive.google.com/file/d/1SsNV59_9rknmFSYrQnWD7sDRiAPbat3d/view?usp=sharing)🔗


# Funções de Entrada e Saída

## Objetivo Geral

_Aprender como receber e exibir informações para o usuário._

## Pré-requisitos

* Python 3 +
* VSCode

## Percurso

* `Etapa 1` __Lendo valores com a função *input*__ 

* `Etapa 2` __Exibindo valores com a função *print*__

# Lendo os valores com a *função input* 

## Função input

_A função *builtin input* é utilizada quando queremos ler dados da entrada padrão (teclado). Ela recebe um argumento do tipo `string`, que é exibido para o usuário na saída padrão (tela). A função lê a entrada, converte para string e retorna o valor._

Exemplo de [builtin input](https://drive.google.com/file/d/1x9o5Bl-lA8tHIrXR-HWEnPZUpCOsr0by/view?usp=sharing)🔗

# Exibindo valores com a *função print*


## __Função print__

_A função builtin print é utilizada quando queremos exibir dados na saída padrão (tela). Ela recebe um argumento obrigatório do tipo `varargs` de objetos 4 argumentos opcionais (sep, end, file e flush). Todos os objetos são convertidos para string, separados por `sep` e terminados por `end`. A string final é exibida para o usuário._

Exemplo de [builtin print](https://drive.google.com/file/d/1wZJnCWRwrrfo7eFsp4JTLHlWxgurO5X5/view?usp=sharing)🔗

|Função|Explicação|
|-|-|
|print(nome, sobrenome) | normal |
|
|print(nome, sobrenome, `end="...\n"`)| Estou pedindo para ele terminar com 3 pontos e estou adicionando uma quebra de linha (`\n` é caractere para uma newline) |
|
|print(nome, sobrenome, `sep="#"`) | `Sep` é "separador |

Exemplo de [print / input](https://drive.google.com/file/d/1soeiFutCf11QgynxDVGTVAUqsRCT-OzO/view?usp=sharing)🔗 

[Código em .py](https://drive.google.com/file/d/18PQnnYrloyc8cUuCiSJcMnJvqTCq4z8_/view?usp=sharing)🔗

## 
# Links Úteis

* [Guicarvalho](https://github.com/digitalinnovationone/trilha-python-dio)🔗
* [docs - Funções - input ](https://docs.python.org/3/library/functions.html#input)🔗
* [docs - Funções - print](https://docs.python.org/3/library/functions.html#print)🔗


# Desafios de projetos: Crie um Portfólio Vencedor!

## PBL, Portfólio, Competências e Empregabilidade

### Aprendizagem Baseada em Projetos (PBL)

_O **Aprendizado Baseado em Projetos** é sobre imergir em grandes ideias e criar soluções tangíveis. Neste método,você constroi projetos práticos que refletem problemas e desafios do mundo real. Esses projetos não apenas aumentam seu conhecimento, mas também demonstram suas competências._

|1️⃣ Portfólio 📦|2️⃣ Destaque 🌟|3️⃣ Oportunidades 🚀|
|-|-|-|
| _Cada projeto concluído reforça suas **habildades**, promove **networking** e  dá **destaque** ao seu portfólio profissional._| _Ao finalizar seus projetos na DIO, você obtém uma **certificação de competências**, um diferencial importante para abrir portas no merdado de trabalho._|Através da **Talent Match**, você tem acesso às melhores oportunidades de emprego no setor de tecnologia. Vamos ajudá-lo a construir a carreira dos seus sonhos. |

### Desenvolva suas Habildades



|   **Hard Skill**            |  **Soft Skill**          |
| -                           | -                        |
| - Linguagens de Programação | - Trabalho em Equipe     |
| - Arquitetura de Sistema    | - Pensamento Crítico     |
| - Banco de Dados            | - Gerenciamento de Tempo |
| - Stacks de Desenvolvimento | - Comunicação            |
| - Ferramentas               | - Liderança              |


# A Importância dos Desafios de Projeto na Prática

## Entendendo o Desafio

**Agora é a sua hora de brilhar e construir um perfil de destaque na DIO! Explore todos os conceitos explorados até aqui e replique (ou melhore, porque não?) este projeto prático. Para isso, crie seu próprio repositório e aumente ainda mais seu portfólio de projetos no GitHub, o qual pode fazer toda diferença em suas entrevistas técnicas.😎**

| _Dica: Se o expert forneceu um repositório GitHub, você pode dar um "fork" no repositório dele para organizar suas alterações e evoluções mantendo uma referência direta ao código-fonte original._ |
|-|

### Repositório Git 

_O Git é um conceito essencial no mercado no mercado de trabalho atualmente, por sempre reforçamos sua importância em nossa metodologia educacional. Por isso, todo código-fonte desenvolvido durante este conteúdo foi versionado no seguinte endereço para que você possa consultá-lo a qualquer momento:_

[Repositório da Eli dio-lab-open-source.](https://github.com/elidianaandrade/dio-lab-open-source)🔗

[Apresentação - Slides](https://academiapme-my.sharepoint.com/:p:/g/personal/renato_dio_me/EYjkgVZuUv5HsVgJUEPv1_oB_QWs8MFBY_PBQ2UAtLqucg?rtime=qBcIgfbM3Eg)🔗
# Operadores Aritméticos

## *Objetivo Geral*

O que são operadores aritméticos e como utilizá-los.

### Pré-requisitos

* Python 3+
* VSCode

### Percurso

|Etapa 1|Etapa 2|
|-|-|

Conhecendo os operadores aritméticos|Precedência de operadores.

## **Etapa 1**

### Conhecendo os operadores aritméticos

#### O que são?

_Os operadores aritméticos executam operações matemáticas, como adição, subtração com operandos._

### Adição, subtração e multiplicação

    # Adição
    print(1 + 1)
    >>> 2
>>>
    # Subtração
    print(10 - 2)
    >>> 8

>>>
    # Multiplicação
    print( 4 * 3)
    >>> 12

### Divisão e divisão inteira

    # Divisão (retorna um float)
    print(12 / 3)
    >>> 4.0
>>>
    # Divisão inteira
    print(12 // 2)
    >>> 6
>>>

### Módulo e exponenciação

    # Módulo (Quantas vezes o três cabe dentro do 10, cabem 3x e sobra 1)
    print(10 % 3)
    >>> 1
>>>
    # Exponenciação (2 ao cubo é = 8)
    print(2 ** 3)
    >>> 8
>>>

## **Etapa 2**

### Precedência de operadores

#### Na matemática

_Na matemática existe uma regra que indica quais operações devem ser executadas primeiro. Isso é útil pois ao analisar uma expressão, a depender da ordem das operações o valor pode ser diferente:_

    x = 10 - 5 * 2
    x é igual a 10 ou 0?

## Na matemática

A definição indica a seguinte ordem como correta:

* Parêntesis
* Expoêntes
* Multiplicações e divisões (da esquerda para a direita)
* Somas e subtrações (da esquerda para a direita)

### Exemplo

    print(10 - 5 * 2)
    >>> 0

    print((10 - 5 ) * 2)
    >>> 10

    print(10 ** 2 * 2) (é o mesmo que 10²)
    >>> 200

    print(10 ** (2 * 2))
    >>> 10000

    print(10 / 2 * 4)
    >>> 20.0

#### Na prática

###### Operação Aritmética na prática
![🔗](https://github.com/Alisson-Fonseca-Frash/imagens/blob/2934808f6e916cd9eb26832120e51e2eef9b0e19/Ex%20de%20operadores%20aritmeticos.png)

##### Precedência dos operadores
*Para forçar o precedente, coloca-se entre Parêntesis.*

    Ex: x = (20 / 2) + (25 * (3 - 4) ** 2)


![🔗](https://github.com/Alisson-Fonseca-Frash/imagens/blob/f737ac23c39cda2e510be35ffaed083fee4824d6/Preced%C3%AAncia%20dos%20operadores.png)

## Links Últeis

* [Trilha Python DIO](https://github.com/guicarvalho/trilha-python-dio)🔗
# Operadores de Comparação (Booleano `bool`)

## Objetivo Geral

*O que são operadores de comparação e como utilizá-los.*

## Pré-requisitos

* Python 3+
* VSCode

## Percurso

| **Etapa 1** |
|-|

*Conhecendo os operadores de comparação*

### O que são?

*São operadores utilizados para comparar dois valores.*

    Ex: Se o valor "a" é maior/menor/igual/diferente que o valor "b"
>>>

### Igualdade

    saldo = 450
    saque = 200

    print(saldo == saque)
    >>> False
>>>
### Diferença

    saldo = 450
    saque = 200
    print( saldo != saque)
    >>> True
### Maior que / maior ou igual

    saldo = 450
    saque = 200
    print(saldo > saque)
    >>> True

    print(saldo >= saque)
    >>> True
>>>
    saldo = 450
    saque = 200
    print(saldo > saque)
    >>> False

    print(saldo <= saque)
    >>> False

## Hands On!

### Na Prática

Operadores de Comparação
![🔗](https://github.com/Alisson-Fonseca-Frash/imagens/blob/eaf4fb53e0fc9fcd5edbf5706ac8eb12f6c1174a/Operadores%20de%20Compara%C3%A7%C3%A3o.png)
# Operadores de Atribuição

## Objetivo Geral

*O que são operadores de atribuição e como utilizá-los.*

## Pré-requisitos

* Python 3+
* VSCode

## Percurso

|Etapa 1|
|-|

Conhecendo os operadores de atribuição

### **Etapa 1**

#### Conhecendo os operadores de atribuição

#### O que são?

*São operadores utilizados para definir o valor inicial ou sobrescrever o valor de uma variável.*

### Atribuição simples

    saldo = 500
    print(saldo)
    >>> 500

### Atribuição com adição

    saldo = 500
    saldo += 200

    print(saldo)
    >>> 700
>>>
### Atribuição com subtração
    saldo = 500
    saldo -= 100

    print(saldo)
    >>> 400

### Atribuição com multiplicação
    saldo = 500
    saldo *= 2

    print(saldo)
    >>> 1000

### Atribuição com divisão
    saldo = 500
    saldo /= 5

    print(saldo)
    >>> 100.0

    saldo = 500
    saldo //= 5

    print(saldo)
    >>> 100

### Atribuição com módulo (resto da divisão)
    saldo = 500
    saldo %= 480

    print(saldo)
    >>> 20

### Atribuição com exponenciação (80 elevado ao quadrado)
    saldo = 80
    saldo **= 2
 
    print(saldo)
    >>> 6400

## Hands On!

### Na prática

![Atribuição adição, subtração, multiplicação e divisão](https://github.com/Alisson-Fonseca-Frash/imagens/blob/409e1c214458bd7b36b3b3f1ab6e58b7b2acf027/Operadores%20de%20Atribui%C3%A7%C3%A3o.png)

![Atribuição exponenciação](https://github.com/Alisson-Fonseca-Frash/imagens/blob/a5047df599efaf37582e2e9de2302b004cedf608/Operadores%20de%20Atribui%C3%A7%C3%A3o%20-%20exponencial.png)
# Operadores Lógicos

## Objetivo Geral

* O que são operadores lógicos e como utilizá-los.

### Pré-requisitos

* Python 3+
* VSCode

## Percurso

| **Etapa 1**|
|-|

*Conhecendo os operadores lógicos.*

### _São operadores utilizados em conjunto com os operadores de comparação, para montar uma expressão lógica. Quando um operador de comparação é utilizado, o resultado retornado é  um booleano (`bool`), dessa forma podemos cominar operadores de comparação com os operadores lógicos, exemplo:_
    op_comparacao + op_logico + op_comparacao... N...

### Exemplo

    saldo = 1000
    saque = 200
    limite = 100

    saldo >= saque
    <span style="color:blue">True</span>

    saque <= limite
    >>> True


## Operador E (`and`)

    saldo = 1000
    saque = 200
    limite = 100

    saldo >= saque and saque <= limite
    >>> False

| _Para que o operador venha ser True, necessita que todas as operadoções sejam verdadeiras. No exemplo acima, o limite (100) é maior que o saque (200), nesse caso, retornará como "False"._|
|-|

## Operador OU (`or`)

    saldo = 1000
    saque = 200
    limite = 100
    
    saldo >= saque or saque <= limite
    >>> True

|Para que o operador venha ser `True`, necessita que apenas um operador seja *verdadeiro*. No exemplo acima, o saldo é maior que o saque. Já para ser falso, todos os operadores precisam ser `False`.|
|-|

## Operador de Negação

    contatos_emergencia = []
    not 1000 > 1500
    >>> True

    not contatos_emergencia
    >>> True

    not "saque 1500;"
    >>> False

    not "  "
    >>> True

|No exemplo acima as respostas resultam em verdadeiras (True). Porém, existe uma Negação (`not`), no exemplo:  not 1000 > 1500 >>> True|
|-|

## Parênteses

|Parênteses serve para limitar a precendência|
|-|

    saldo = 1000
    saque = 250
    limite = 200
    conta_especial = True

    saldo >= saque and saque >= limite or conta_especial and saldo >= saque
    >>> True

    (saldo >= saque and saque <= limite) or (conta_especial and saldo >= saque)
    >>> True 
    (essa está mais simples de ser lida)

## Hands On!

### Na prática

![Operadores lógicos básico](https://github.com/Alisson-Fonseca-Frash/imagens/blob/75c89ec2adb8d6bdaaa937f2db8ad4ac0a235d7d/Operadores%20logicos%20basico.png)

![Operadores lógicos avançado](https://github.com/Alisson-Fonseca-Frash/imagens/blob/18873819f108440c757f1d52b4fdd17d0d7ea201/Operadores%20logicos%20avan%C3%A7ado.png)

|Dica: não criem uma operação lógica muito grande, tente sempre fazer uma lógica pequena e compreensível de ser lida e resolvida.|
|-|

Por exemplo:

![](https://github.com/Alisson-Fonseca-Frash/imagens/blob/852aa79a33177b9893188804a8cbc8af42299d9b/Operadores%20logicos%20avan%C3%A7ado%20-%20Completo.png)
