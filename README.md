
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
    >>> True

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

# Operadores de Identidade

## Objetivo Geral

_O que são operadores de identidade e como utilizá-los._

## Pré-requisitos

* Python 3+
* VSCode

## Percurso

| **Etapa 1**|
|-|

Conhecendo os operadores de identidade

### O que são?

_São operadores utilizados para comparar se os dois objetos testados ocupam a mesma posição na memória._

#### Comandos:

* `is`
* `is not`

### Exemplo

    curso = "Curso de Python"
    nome_curso = curso
    saldo, limite = 200, 200

    curso `is` nome_curso
    >>> True
    
    curso `is not` nome_curso
    >>> False

    saldo `is` limite
    >>> True
  
### Hands On!

### Na prática

![Operadores de identidade](https://github.com/Alisson-Fonseca-Frash/imagens/blob/17f98d3832b33ca35e2ed5ae0449a95937e31a6a/operadores%20de%20identidade.png)


# Operadores de Associação

## Objetivos Geral

_O que são operadores de associação e como utilizá-los._

## Pré-requisitos

* Python 3+
* VSCode

## Percurso

| **Etapa 1**|
|-|

Conhecendo os operadores de comparação.

### O que são?

_São operadores utilizados para verificar se um objeto está presente em uma sequência._

* `in`
* `not in`

#### Exemplo

    curso = "Curso de Python"
    frutas = ["laranja", "uva", "limão"]
    saques = [1500, 100]

    "Python"  in curso
    >>> True

    "maçã"  not in frutas
    >>> True

    200 in saques
    >>> False

### Hands On!

#### Na Prática

![Operadores de Associação - `in` ](https://github.com/Alisson-Fonseca-Frash/imagens/blob/4e3e58f794596e2c2364292b13a2f24fa8cceb94/operadores%20de%20Associa%C3%A7%C3%A3o%20-%201.png)


![Operadores de associação - exemplo de quando se coloca com letra indiferente](https://github.com/Alisson-Fonseca-Frash/imagens/blob/67d4a1ab8ef5c162eb09ecba6d4caa6ee31c3764/operadores%20de%20Associa%C3%A7%C3%A3o%20-%202.png)

![Exemplo de quando usar o "not in" e "in" ](https://github.com/Alisson-Fonseca-Frash/imagens/blob/531aaf9aebf3b82efa540545bce033eda8259bbc/operadores%20de%20Associa%C3%A7%C3%A3o%20-%203.png)

![Exemplo de String usando variaveis](https://github.com/Alisson-Fonseca-Frash/imagens/blob/24c2cfa59876753dd2affb96b36407607065424a/operadores%20de%20Associa%C3%A7%C3%A3o%20-%204.png)

* Lembrando sempre de colocar as palavras corretamente! Caso venha colocar divergentes, retornará erros. (ex: a e A)

## Arquivos para estudos

* 9 - [Operadores Aritméticos](https://github.com/Alisson-Fonseca-Frash/dio-curso-resumo-em-geral/blob/4b8f67b6011e1caff917bb7e86361cfac202ec8f/09%20-%20%5BDio%5D%20Operadores%20aritm%C3%A9ticos.pptx)🔗

* 10 - [Operadores de Comparação](https://github.com/Alisson-Fonseca-Frash/dio-curso-resumo-em-geral/blob/4b8f67b6011e1caff917bb7e86361cfac202ec8f/10%20-%20%5BDio%5D%20Operadores%20de%20compara%C3%A7%C3%A3o.pptx)🔗

* 11 - [Operadores de Atribuição](https://github.com/Alisson-Fonseca-Frash/dio-curso-resumo-em-geral/blob/4b8f67b6011e1caff917bb7e86361cfac202ec8f/11%20-%20%5BDio%5D%20Operadores%20de%20atribui%C3%A7%C3%A3o.pptx)🔗

* 12 - [OPeradores Lógicos](https://github.com/Alisson-Fonseca-Frash/dio-curso-resumo-em-geral/blob/4b8f67b6011e1caff917bb7e86361cfac202ec8f/12%20-%20%5BDio%5D%20Operadores%20l%C3%B3gicos.pptx)🔗

* 13 - [Operadores de Identidade](https://github.com/Alisson-Fonseca-Frash/dio-curso-resumo-em-geral/blob/4b8f67b6011e1caff917bb7e86361cfac202ec8f/13%20-%20%5BDio%5D%20Operadores%20de%20identidade.pptx)🔗

* 14 - [Operadores de Associação](https://github.com/Alisson-Fonseca-Frash/dio-curso-resumo-em-geral/blob/4b8f67b6011e1caff917bb7e86361cfac202ec8f/14%20-%20%5BDio%5D%20Operadores%20de%20associa%C3%A7%C3%A3o.pptx)🔗
# Estruturas condicionais e de repetição

## O que iremos aprender?

* Indentação e blocos
* Estruturas condicionais
* Estruturas de repetição


## Materiais de apoio

[Clique aqui](https://academiapme-my.sharepoint.com/personal/kawan_dio_me/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fkawan%5Fdio%5Fme%2FDocuments%2FSlides%20dos%20Cursos%2FPython%20%2D%20M%C3%B3dulo%20I%20%2D%20Fundamentos%2FCurso%204&ga=1)🔗
# Indentação e blocos

## Objetivo Geral

_Aprender como o interpretador Python utiliza a indentação do código para delimitar os blocos de comandos._

### Pré-requisitos

* Python 3+
* VSCode

### Percurso

| **Etapa 1**|
|-|

Indentação e os blocos de comando.

## A estética

_Indentar código é uma forma de manter o código fonte mais légivel e manutenível. Mas em Python ela exerce um segundo papel, através da indentação o interpretador consegue determinr onde um bloco de comando inicia e onde ele termina._

## Bloco de comando

_As linguagens de programação costumam utilizar caracteres ou palavras reservadas para terminar o início e fim do bloco. Em `Java` e `C` por exemplo, utilizamos chaves:_

### Bloco em Java

    void sacar(double valor) { // início do bloco do método
      if (this.saldo >= valor) { // início do bloco do if
        this.saldo -= valor;
        } // fim do bloco do if
    } // fim do bloco do método

### Bloco no Java sem formatar

    void sacar(double valor){ // início do bloco do método
    if (this.saldo >= valor){ // início do bloco if
    this.saldo -= valor;
    } // fim do bloco do if
    } // fim do bloco do método

## Utilizando espaços

_ Existe uma convenção em Python, que define as boas práticas para escrita de código na linguagem. Nesse documento é indicado utilizar 4 espaços em branco por nível de indentação, ou seja, a cada novo bloco adicionamos 4 novos espaços em branco.

### Ex de Bloco em Python

    def sacar(self, valor: float) ➡️ None: # início do bloco do método

    if self.saldo >= valor: # início do bloco do if
        self.saldo -= valor
      # fim do bloco do if
    # fim do bloco do método

### Isso não funciona no Python

    def sacar(self, valor: float) ➡️ None: # início do bloco do método
    if self.saldo >= valor: # início do bloco do if
    self.saldo -= valor
    # fim do bloco do if
    # fim do bloco do método

### Qual versão é mais fácil de ler?

    void sacar(double valor) { 
    if (this.saldo >= valor) { 
    this.saldo -= valor;}}

      def sacar(self, valor: float) ➡️ None:
          if self.saldo >= valor)
              self.saldo -= valor

## Hands On!

### Vamos na Prática

![Exemplo de Bloco em Python - simples e sem erro](https://github.com/Alisson-Fonseca-Frash/imagens/blob/74defcda7f15e44efde67c79c1c7c8c40fb64718/Exemplo%20de%20%20Bloco%20em%20Python%20-%20Simples%20-%20sem%20erro.png)

![Exemplo de  Bloco em Python - Simples - com erro - não sacado](https://github.com/Alisson-Fonseca-Frash/imagens/blob/49e6b7f4707d374d0332b4c8d96c530dd3277da6/Exemplo%20de%20%20Bloco%20em%20Python%20-%20Simples%20-%20com%20erro%20-%20n%C3%A3o%20sacado.png)


# Estruturas condicionais
## Objetivo Geral

_O que são as estruturas condicionais e como utilizá-las._

### Pré-requisitos

* Python
* VSCode

### Percurso

| **Etapa 1**|
|-|

* if / if-else/ elif

|**Etapa 2**|
|-|

* if aninhado

|**Etapa 3**|
|-|

* if ternário

### O que são?

_A estrutura condicional permite o desvio de fluxo de controle, quando determinadas expressões lógicas são atendidas._

## if

| Para criar uma estrutura condicional simples, composta por um único desvio, podemos utilizar a palavra reservada `if`. O comando irá testar a expressão lógica, e em caso de retorno verdadeiro as ações presentes no bloco de código do `if` serão executadas. |
|-|

### Exemplo

    saldo = 2000.0
    saque = float(input("informe o valor do saque: "))
    if saldo >= saque:
        print("Realizando saque!")

    if saldo < saque:
        print("Saldo insuficiente!")

## if-else

| Para criar uma estrutura condicional com dois desvios, podemos utilizar as palavras reservada `if  e else`. Como sabemos se a expressão lógica testada no if for verdadeira, então o bloco de código do if será executado. Caso contrário o bloco de código do else será executado. |
|-|

### Exemplo

    saldo = 2000.0
    saque = float(input( "Informe o valor do saque: "))

    if saldo >= saque:
        print( "Realizando saque!" )
        
    else:
        print(" Saldo insuficiente!" )

## if / elif / else

| Em alguns cenários queremos mais de dois desvios, para isso podemos utilizar a palavra reservada `elif`. O elif é composto por uma nova expressão lógica, que será testada e caso retorne verdadeiro o bloco de código do elif será executado. Não existe um número máximo de elifs que podemos utilizar, porém evite criar grandes estruturas condicionais, pois elas aumentam a complexidade do código.|
|-|

### Exemplo

    opcao = int(input("Informe uma opção: [1] Sacar \n[2] Extrato: "))

    if opcao == 1:
        valor = float(input("Informe a quantia para o saque: "))
        # ...
    elif opcao == 2:
        print("Exibindo o extrato ...")
    else:
        sys.exit("Opção inválida")

## Hands On!
### Vamos para prática!

![Exemplo de `if e else`](https://github.com/Alisson-Fonseca-Frash/imagens/blob/91be02eceeb7036bdb5f7bb4999f64716da6b8be/Estrutura%20condicionais%20-%20%20if%20e%20else.png)

![Estrutura condicionais -  if - else - elif.png](https://github.com/Alisson-Fonseca-Frash/imagens/blob/e6df6a568aa39b0f60a81516321793222861c008/Estrutura%20condicionais%20-%20%20if%20-%20else%20-%20elif.png)

## if aninhado

| Podemos criar estruturas condicionais aninhadas, para isso basta adicionar estruturas `if/elif/else` dentro do bloco de código de estruturas if/elif/else.|
|-|

### Exemplo

    if conta_normal:
        if saldo >= saque:
            print("Saque realizado com sucesso!")
        elif saque <= (saldo + cheque_especial):
            print("Saque realizado com uso do cheque especial!")

    elif conta_universitaria:
        if saldo >= saque:
          print("Saque realizado com 
          sucesso!")
        else:
            print("Saldo insuficiente!")

![Exemplo de Estrutura condicionais - if aninhada](https://github.com/Alisson-Fonseca-Frash/imagens/blob/6e2b57b3d2a67787aa6883c6581bfea094b1e54d/Estrutura%20condicionais%20-%20%20if%20%20aninhada.png)

![Estrutura condicionais -  if  aninhada - invertida as contas.png](https://github.com/Alisson-Fonseca-Frash/imagens/blob/62abd94fd9cbcf35a5cab9c99c47cc1a1c4d05e0/Estrutura%20condicionais%20-%20%20if%20%20aninhada%20-%20invertida%20as%20contas.png)

![Estrutura condicionais -  if  aninhada - ex de erro de leitura](https://github.com/Alisson-Fonseca-Frash/imagens/blob/ac97b18e7e3b2c134da51f5ef19a24abc9ce95c7/Estrutura%20condicionais%20-%20%20if%20%20aninhada%20-%20ex%20de%20erro%20de%20leitura.png)

## if ternário

| O `if ternário` permite escrever uma condição em uma única linha. Ele é composto por três partes, a primeira parte é o retorno caso a expressão retorne verdadeiro, a segunda parte é a expressão lógica e a terceira parte é o retorno caso a expressão não seja atendida.|
|-|

### Exemplo

    status = "Sucesso" if saldo >= saque else "Falha"

    print(f"{status} ao realizar o saque!")

![Estrutura condicionais -  if  ternário - com e sem saque](https://github.com/Alisson-Fonseca-Frash/imagens/blob/bca8f0a9b065474a25a8717c96a35c8d65b183b0/Estrutura%20condicionais%20-%20%20if%20%20ternario%20-%20com%20e%20sem%20saque.png)


# Estruturas de Repetição

## Objetivo Geral

_Conhecer as estruturas de repetição `for e while` e quando utilizá-las._

### Pré-requisitos

* Python 3+
* VSCode

### Percurso

|**Etapa 1**|
|-|

O que são estruturas de repetição?

|**Etapa 2**| 
|-|

Comando `for` e a função `built-in range`

|**Etapa 3**|
|-|

Comando `while`

#
#### O que são estruturas de repetição?

|_São estruturas utilizadas para repetir um trecho de código um determinado número de vezes. Esse número pode ser conhecido previamente ou determinado através de uma expressão lógica._|
|-|

### Exemplo sem repetição

    # Receba um número do teclado e exiba os 2 números seguintes
    
    a = int(input("Informe um número inteiro: "))
    print(a)

    a += 1
    print(a)

    a += 1
    print(a)

### Exemplo com repetição

    # Receba um número do teclado e exiba os 2 números seguintes
    a = int(input("Informe um número inteiro: "))
    print(a)
    
    repita 2 vezes: (simulação, só pra entender o funcionamento)
        a += 1
        print(a)

## Comando `for`

|_O comando `for` é usado para percorrer um objeto iterável. Faz sentido usar *for* quando sabemos o número exato de vezes que nosso bloco de código deve ser executado, ou quando queremos percorrer um objeto iterável._|
|-|

### Exemplo de _for_

    texto = input("Informe um texto: ")
    VOGAIS = "AEIOU"
    
    for letra in texto:
          if letra.upper() in VOGAIS:
              print(letra, end=" ")

    print( ) # adiciona uma quebra de linha

![Estrutura de repeticao - ex de for](https://github.com/Alisson-Fonseca-Frash/imagens/blob/da604a2e9a6eef64972559b1e8ed7df8764844d2/Estrutura%20de%20repeticao%20-%20ex%20de%20for.png)

### Exemplo de `for/else`

    texto = input("Informe um texto: ")
    VOGAIS = "AEIOU"

    for letra in texto:
          if letra.upper() in VOGAIS:
             print(letra, end=" ")
    
    else:
        print( ) # adiciona uma quebra de linha

![Estrutura de repeticao - ex de `for e else`](https://github.com/Alisson-Fonseca-Frash/imagens/blob/cebc86c558975ad49b9bac7b6c84cb581feff58e/Estrutura%20de%20repeticao%20-%20ex%20de%20for%20e%20else.png)

## Função range

|Range é uma função `built-in` do Python, ela é usada para produzir uma sequência de números inteiros a partir de um ínicio (inclusivo) para um fim (exclusivo). Se usarmos range(i, j) será produzido: i, i+1, i+2, i+3, ..., j-1. Ela reecbe 3 argumentos: stop (obrigatório), start (opcional) e step opcional.| 
|-|

### Exemplo de `range`

    # range (stop) -> range object
    # range (start, stop[, step]) -> range object

    list(range(4))
    >>> [0, 1, 2, 3]

### Utilizando `range com for`

    for numero in range(0,11):
        print(numero, end=" ")
    
    >>> 0 1 2 3 4 5 6 7 8 9 10

    # exibindo a tabuada do 5
    for numero in range(0, 51, 5):
        print(numero, end=" ")

    >>> 0 5 10 15 20 25 30 35 40 45 50

![Estrutura de repeticao - ex de range com for](https://github.com/Alisson-Fonseca-Frash/imagens/blob/24c47790e868e2691b8a6b328cbd06d9ef444897/Estrutura%20de%20repeticao%20-%20ex%20de%20range%20com%20for.png)

![Estrutura de repeticao - ex de range com for - ex iteravel e ex built-in](https://github.com/Alisson-Fonseca-Frash/imagens/blob/b58589aac4e4c12c8afc29755ea03020d6b7ec57/Estrutura%20de%20repeticao%20-%20ex%20de%20range%20com%20for%20-%20ex%20iteravel%20e%20ex%20built-in.png)

## Comando `while`

|O comando while é usado para repetir um bloco de código várias vezes. Faz sentido usar while quando não sabemos o número exato de vezes que nosso bloco de código deve ser executado.|
|-|

### Exemplo de `while`

    opcao = -1
    while opcao != 0:
        opcao = int(input("[1] Sacar \n[2] Extrato \n[0] Sair \n: "))

        if opcao == 1:
            print("Sacando ... ")
        elif opcao == 2:
            print("Exibindo o extrato ... ")

### `while/else`

    opcao = -1
    while opcao != 0:
        opcao = int(input("[1] Sacar \n[2] Extrato \n[0] Sair \n: "))

        if opcao == 1:
            print("Sacando ... ")
        elif opcao == 2:
            print("Exibindo o extrato ... ")

    else:
        print("Obrigado por usar nosso sistema bancário, até logo!")

## Exemplo de `break` (Fork)

![Estrutura de repeticao - ex de break - Usado para parar o procedimento assim que a ação for concluída/feita](https://github.com/Alisson-Fonseca-Frash/imagens/blob/13d89fcd92d17898fcc319de114b59c5aac43637/Estrutura%20de%20repeticao%20-%20ex%20de%20break.png)

![Estrutura de repeticao - ex de break com for - Usado para parar o procedimento assim que a ação for concluída/feita](https://github.com/Alisson-Fonseca-Frash/imagens/blob/b912e3e9ac5808f2cbcda410efa4f3f302a1439a/Estrutura%20de%20repeticao%20-%20ex%20de%20break%20com%20for%20-%20Usado%20para%20parar%20o%20procedimento%20assim%20que%20a%20a%C3%A7%C3%A3o%20for%20concluida-feita.png)

    for numero in range(100):

    if numero == 12:
        continue
    print(numero, end=" ")
    >>> 0 1 2 3 4 5 6 7 8 9 10 11 13 14 15 
    16 17 18 19 20 21 22 23 24 25 26 27 28 
    29 30 31 32 33 34 35 36 37 38 39 40 41 
    42 43 44 45 46 47 48 49 50 51 52 53 54 
    55 56 57 58 59 60 61 62 63 64 65 66 67 
    68 69 70 71 72 73 74 75 76 77 78 79 80 
    81 82 83 84 85 86 87 88 89 90 91 92 93 
    94 95 96 97 98 99

* Usando esse comando, nós conseguimos pular o número 12.

![Estrutura de repeticao - ex de continue - Usado para pular um numero no procedimento)](https://github.com/Alisson-Fonseca-Frash/imagens/blob/a0461cf276b7bd2cc76b2a0538989094a4fb253c/Estrutura%20de%20repeticao%20-%20ex%20de%20continue%20-%20Usado%20para%20pular%20um%20numero%20no%20procedimento.png)


# Manipulando Strings com Python - Dominando Strings e Fatiamento

## Objetivo Geral

_Conhecer métodos úteis para manipular objetos do tipo string, como interpolar valores de variáveis e entender como funciona o fatiamento._

### Pré-requisitos

* Python 3+
* VSCode

## O que iremos aprender?

|**Etapa 1**|
|-|

* Conhecendo métodos úteis da classe string

|**Etapa 2**|
|-|

* Interpolação de variáveis
|**Etapa 3**|
|-|

* Fatiamento de string
|**Etapa 4**|
|-|

* String múltiplas linhas

### Material de apoio

* Está disponível [AQUI.](https://academiapme-my.sharepoint.com/:f:/g/personal/kawan_dio_me/EuoIz_n9KVhCu1FlPzGOh0UBtc3llVdlZ0KJacWo_QXIKQ?e=tSHYzd)🔗
# Conhecendo métodos úteis da classe string

## Introdução

_A classe String do Python é famosa por ser rica em métodos e possuir uma interface muito fácil de trabalhar._

_Em algumas linguagens manipular sequências de caracteres não é um trabalho trivial, porém, em Python esse trabalho é muito simples._

### Maiúscula, minúscula e título

    curso = "pYtHon"

    print(curso.upper()) # Ficará tudo em maiúsculo
    >>> PYTHON 

    print(curso.lower()) # Ficará tudo em minúsculo
    >>> python 

    print(curso.title()) # Ficará com a inicial maiúsculo
    >>> Python

### Eliminando espaços em branco

    curso = "   Python "

    print(curso.strip()) # Remove o espaço em branco do lado esquerdo e direito.
    >>> "Python"

    print(curso.lstrip()) # Remove o espaço em branco do lado esquerdo. (Left strip)
    >>> "Python "

    print(curso.rstrip()) # Remove o espaço em branco do lado direito. (Right strip)
    >>> "   Python "

### Junções e centralização

    curso = "Python"

    # Centralização:
    print(curso.center(10, "#")) # Tem dois argumentos - quantidade de caractere / argumento opcional, pode colocar o que quer no espaço em branco.
    >>> "##Python##"

    # Junção: mais usado em listas
    
    print(".".join(curso)) # .join - Vai passar letra a letra e adicionar um .(ponto final) como foi pedido.
    >>> "P.y.t.h.o.n"


# Interpolação de variáveis

## Introdução

_Em Python temos 3 formas de interpolar variáveis em strings, a primeira é usando o sinal `%`, a segunda é utilizando o método `format` e a última é utilizando `f` strings._

_A primeira forma não é atualmente recomendada e seu uso em Python 3 é raro, por esse motivo iremos focar nas 2 últimas._ 

### Old style

    nome = "Alisson"
    idade = 30
    profissao = "Programador"
    linguagem = "Python"

    print("Olá, me chamo %s. Eu tenho %d anos de idade, trabalho como %s e estou matriculado no curso de %s." % (nome, idade, profissao, linguagem))

    >>> Olá, me chamo Alisson. Eu tenho 30 anos de idade, trabalho como Programador e estou matriculado no curso de Python.
>>>

| Você pode usar a `%s` quando quer usar valores do tipo strings. Já `%d` para valores inteiros, e por fim `%f` para ponto flutuantes.|
|-|

### Método `format`

    nome = "Alisson"
    idade = 30
    profissao = "Programador"
    linguagem = "Python"

    print("Olá, me chamo {}. Eu tenho {} anos de idade, trabalho como {} e estou matriculado no curso de {}." .format(nome, idade, profissao, linguagem))

    print("Olá, me chamo {3}. Eu tenho {2} anos de idade, trabalho como {1} e estou matriculado no curso de {0}." .format(linguagem, profissao, idade, nome))

    print("Olá, me chamo {nome}. Eu tenho {idade} anos de idade, trabalho como {profissao} e estou matriculado no curso de {linguagem}." .format(nome=nome, idade=idade, profissao=profissao, linguagem=linguagem))

    print("Olá, me chamo {nome}. Eu tenho {idade} anos de idade, trabalho como {profissao} e estou matriculado no curso de {linguagem}." .format(**pessoa)) # Foi feito um dicionário (dados = {"nome": Guilherme, "idade": 30, "profissao": programacao, "linguagem": Python}). 

    >>> Olá, me chamo Alisson. Eu tenho 30 anos de idade, trabalho como Programador e estou matriculado no curso de Python.
>>>

### f-string 

    nome = "Alisson"
    idade = 30
    profissao = "Programador"
    linguagem = "Python"

    print(f"Olá, me chamo {nome}. Eu tenho {idade} anos de idade, trabalho como {profissao} e estou matriculado no curso de {linguagem}.")

    >>> Olá, me chamo Alisson. Eu tenho 30 anos de idade, trabalho como Programador e estou matriculado no curso de Python.
>>>

### Formatar strings com f-string

    PI = 3.14159
    
    print(f"Valor de PI: {PI:.2f}" )
    >>> "Valor de PI: 3.14"

    print(f"Valor de PI: {PI:10.2f}") # adiciona 10 espaços
    >>> "Valor de PI:      3.14"
>>>


# Fatiamento de string

## Introdução

|Fatiamento de strings é uma técnica utilizada para retornar substrings (partes da string original), informando inicio (`start`), fim (`stop`), e passo (`step`): [start: stop:[ , step]].|
|-|

### Fatiamento

    nome = "Alisson dos Santos Fonseca Almeida"

    nome[0] # Chamado de "start". É de onde se inicia, como o nome já diz.
    >>> "A"

    nome[:7] # Com esse fatiamento começa do 0 que é A e termina em 6 que é N  
    >>> "Alisson"

    nome[8:] # Com esse fatiamento começa do 8 que é "d" e vai até o fim
    >>> "dos Santos Fonseca Almeida"

    nome[11:17] # Conhecido como substring, é um conjunto, um pedaço da string.
    >>> "Santos"

     nome[11:17:2] # Chamado de "step" Pulará de 2 em 2 até completar o pedido que foi de 11 à 17
     >>> "Sno"

     nome[:] # Retorna uma cópia da string
     >>> "Alisson dos Santos Fonseca Almeida"

     nome[::-1] # Irá espelhar a string, no caso, ficará invertido
     >>> "adiemlA acesnoF sotnaS sod nossilA"


# String múltiplas linhas

## Introdução
_Strings de múltiplas linhas são definidas informando 3 aspas simples ou duplas durante a atribuição. Elas podem ocupar várias linhas do código, e todos os espaços em branco são incluído na string final._

### Strings triplas

    nome = "Alisson"
    mensagem = f"""
    Olá meu nome é {nome},
    Eu estou aprendendo Python
    """
    >>>

    Olá meu nome é Alisson
    Eu estou aprendendo Python

### Exemplo de preservação de espaços

    nome = "Alisson"

    mensagem = f'''
        Olá meu nome é {nome},
     Eu estou aprendendo Python.
          Essa mensagem tem diferentes recuos.
    '''
    >>>
        Olá meu nome é {nome},
     Eu estou aprendendo Python.
          Essa mensagem tem diferentes recuos.

* Não há diferença entre aspas duplas ("") ou aspas simples ('').


### Links Úteis

* [https://github.com/guicarvalho/trilha-python-dio](https://github.com/guicarvalho/trilha-python-dio)  🔗
* [https://docs.python.org/pt-br/3/libary/string.html](https://docs.python.org/pt-br/3/libary/string.html)  🔗
* [https://docs.python.org/pt-br/3/libary/stdtypes.html#te](https://docs.python.org/pt-br/3/libary/stdtypes.html#te)   🔗
# Dominando Funções Python
##  O que iremos aprender?

| **Funções Python - Parte 01**|
|-|
>>>
|**Funções Python - Parte 02**|
|-|


## **Objetivo Geral

_Entender como funciona as funções em Python._

### Pré-requiisitos

* Python 3+
* VSCode

## Percurso

|Etapa 1|
|-|

**Estudo aprofundado sobre funções**


### Materiais de apoio

Os slides estarão disponíveis neste [LINK](https://academiapme-my.sharepoint.com/:p:/g/personal/nubia_dio_me/EaMAaOx_Bq5JqkD9h-Ksh0kB6tFp8Uj38OIjOy-hALypeQ?e=DnarB4) 🔗# Funções Python - Parte 01
## O que são funções?

| _Função é um bloco de código identificado por um nome e pode receber uma lista de parâmetros, esses parâmetros podem ou não ter valores padrões. Usar funções torna o código mais legível e possibilita o reaproveitamento de código. Programar baseado em funções, é o mesmo que dizer que estamos programando de maneira estruturada._ |
|-|

### Exemplo

    def exibir_mensagem():
        print("Olá mundo!")
    
    def exibir_mensagem_2(nome): # Sou obrigado a declarar o argumento da minha função. Caso não passe um valor, retornará um erro. 
        print(f"Seja bem vindo{nome}!")
    
    def exibir_mensagem_3(nome="Anônimo"): # Aqui já está completa.
        print(f"Seja bem vindo {nome}!")
    

    exibir_mensagem()
    exibir_mensagem_2(nome="Alisson")
    exibir_mensagem_3()
    exibir_mensagem_3(nome="Frash")

* Qual o papel da função `def`?

| É informar ao interpretador que "exibir_mensagem()" é um nome de uma função.|
|-|

### Retornando valores

_Para retornar um valor, utilizamos a palavra reserada return. Toda função Python retorna `None` por padrão. Diferente de outras linguagens de programação, em Python uma função pode retornar mais de um valor._

#### Exemplo

    def calcular_total(numeros):
        return sum(numeros)

    def retorna_antecessor_e_sucessor(numero):
        antecessor = numero - 1
        sucessor = numero + 1

        return antecessor, sucessor
        
    calcular_total([10, 20, 34]) # 64
    retorna_antecessor_e_sucessor(10) # (9, 11) irá retorna uma tupla, ou seja, a tupla é uma estrutura imutável

### O que é uma `tupla`?


Uma tupla em Python é uma coleção ordenada e imutável de elementos. Isso significa que, uma vez criada, uma tupla não pode ser alterada, ao contrário das listas, que são mutáveis. As tuplas são representadas por parênteses, e seus elementos são separados por vírgulas.

Aqui está um exemplo simples de uma tupla:

    ```python
    # Criando uma tupla
    minha_tupla = (1, 2, 3, "a", "b", "c")

    # Acessando elementos da tupla
    print(minha_tupla[0])  # Saída: 1
    print(minha_tupla[3])  # Saída: "a"
    ```

* Tuplas são úteis quando você precisa de uma coleção de elementos que não deve ser alterada ao longo do tempo, como coordenadas geográficas ou dados de configuração.


### Argumentos nomeados

Funções também podem ser chamadas usando argumentos nomeados da forma chave=valor.

#### Exemplo

      def salvar_carro(marca, modelo, ano, placa):
          # salva carro no banco de dados...
          print(f"Carro inserido com sucesso! {marca}/{modelo}/{ano}/{placa}")
  
      salvar_carro("Fiat", "Palio", 1999, "ABC-0432")
      salvar_carro(marca="Fiat", modelo="Palio", ano=1999, placa="ABC-0432")
      salvar_carro(**{"marca": "Fiat", "modelo": "Palio", "ano": 1999, "placa": "ABC-0432"})

      >>> # Carro inserido com Sucesso! Fiat/Palio/1999/ABC-0432


### Args e kwargs

_Podemos combinar parâmetros obrigatórios com `args` e `kwargs`. Quando esses são definidos (*args e **kwargs), o método recebe os valores como tupla (args) e dicionário (kwargs) respectivamente._

#### Exemplo

        def exibir_poema(data_extenso, *args, **kwargs):
            texto = "\n".join(args)
            meta_dados = "\n".join([f"{chave.title()}]): {valor}" for chave, valor in kwargs.items()])
            mensagem = f"{data_extenso}\n\n{texto}\n\n{meta_dados}"
            print(mensagem)

        exibir_poema("Zen of Python", "Beautiful is bette than ugly.", autor="Tim Peters", ano=1999)

## Resumo sobre: `"data_extenso"`, `"*args"` e `"**kwargs"`

Parece que você está pedindo um resumo de algo relacionado a "data_extenso", "args" e "kwargs". Esses termos são frequentemente usados em programação, especialmente em Python. Vou explicar brevemente cada um:

1. **data_extenso**: Geralmente, refere-se a uma função ou biblioteca que converte datas em formato numérico para um formato textual. Por exemplo, transformar "20/09/2024" em "20 de setembro de 2024".

2. **args**: Em Python, `*args` é usado para passar uma lista de argumentos variáveis para uma função. Isso permite que a função receba um número indefinido de argumentos posicionais.

3. **kwargs**: Similarmente, `**kwargs` permite passar um dicionário de argumentos nomeados para uma função. Isso é útil quando você quer que a função aceite um número indefinido de argumentos nomeados.
#  Funções Python - Parte 02

## Parâmetros especiais

_Por padrão, argumentos podem ser passados para uma função Python tanto por posição quanto expliitamente pelo nome. Para uma melhor legibilidade e desempenho, faz sentido restringir a maneira pelo qual argumentos possam ser passados, assim um desenvolvedor precisa apenas olhar para a definição da função para determinar se os itens são passados **por posição, por posição e nome, ou por nome**._

![🔗](https://github.com/Alisson-Fonseca-Frash/imagens/blob/98cd1ed4f5cb31267763cbbfae5b6d99b46fc8df/Parametros%20especiais.png)

### Positional only

        def criar_carro(modelo, ano, placa, /, marca, motor combustivel):
            print(modelo, ano, placa, marca, motor, combustivel)

        
        criar_carro("Palio", 1999, "ABC-0432", marca="Fiat", motor="1.0", combustivel="Gasolina") # válido

        criar_carro(modelo="Palio", ano=1999, placa="ABC-0432", marca="Fiat", motor="1.0", combustivel="Gasolina") # inválido

### Keyword only

        def criar_carro(*, modelo, ano, placa, marca, motor, combustivel):
            print(modelo, ano, placa, marca, motor combustivel)

        
        criar_carro(modelo="Palio", ano=1999, placa="ABC-0432", marca="Fiat", motor="1.0", combustivel="Gasolina) # válido

        criar_carro("Palio", 1999, "ABC-0432", marca="Fiat", motor="1.0", combustivel="Gasolina") # inválido

### Keyword and Positional only (híbrido)

        def criar_carro(modelo, ano, placa, /, *, marca, motor, combustivel):
            print(modelo, ano, placa, marca, motor, combustivel)

        criar_carro("Palio", 1999, "ABC-0432", marca="Fiat", motor="1.0", combustivel="Gasolina") # válido

        criar_carro(modelo="Palio", ano=1999, placa="ABC-0432", marca="Fiat", motor="1.0", combustivel="Gasolina) # inválido

* Quando você quer argumentos nomeados, força com `*`. Já quando quiser por posição, usa a `/`.

## Objetos de primeira classe

_Em Python tudo é objeto, dessa forma **funções também são objetos** o que as tornam objetos de primeira classe. Com isso podemos **atribuir funções a variáveis, passá-las como parâmetro para funções, usá-las como valores em estruturas de dados** (listas, tuplas, dicionários, etc) e usar como valor de retorno para uma função (closures)._ 

### Exemplo
        def somar(a, b):
            return a + b

        def exibir_resultado(a, b, funcao):
            resultado = funcao(a, b)
            print(f"0 resultado da operação é {a} + {b} = {resultado}")

        exibir_resultado(10, 10, somar) # O resultado da operação 10 + 10 = 20

### Escopo local e Escopo global

_Python trabalha com escopo local e global, dentro do bloco da função o escopo é local. Portanto alterações ali feitas em objetos imutáveis serão perdidas quando o método terminar de ser executado. Para usar objetos globais utilizamos a palavra-chave `global`, que informa ao interpretador que a variável que está sendo manipulada no escopo local é global. Essa **NÃO é uma boa prática e deve ser evitada.**_ 

#### Exemplo

      salario = 2000

      def salario_bonus(bonus):
      global salario 
      salario += bonus
      return salario
  
      novo_salario = salario_bonus(500) # 2500

      print(novo_salario)
      >>> 2500

* No exemplo acima, o "salario = 2000" está no 'global', para podermos chamá-la usando `global`.
# Desafio: Criando um Sistema Bancário

## Objetivo Geral

| _Criar um sistema bancário com as operações: sacar, depositar e visualizar extrato._
|-|

### Desafio

##### Simulando a criação:

_Fomos Contratados por um grande banco para desenvolver o seu novo sistema. Esse banco deseja modernizar suas operações e para isso escolheu a linguagem Python. Para a primeira versão do sistema devemos implementar apenas 3 operações: depósito, saque e extrato._

### Operação de depósito

| Deve ser possível depositar valores positivos para a minha conta bancária. A v1 do projeto trabalha apenas com 1 usuário, dessa forma não precisamos nos preocupar em identificar qual é o número da agência e conta bancária. Todos os depósitos devem ser armazenados em uma variável e exibidos na operação de extrato.|
|-|

### Operação de saque

| O sistema deve permitir realizar 3 saques diários com limite máximo de R$ 500,00 por saque. Caso o usário não tenha saldo em conta, o sistema deve exibir uma mensagem informando que não será possível sacar o dinheiro por falta de saldo. Todos os saques devem ser armazenados em uma variável e exibidos na operação de extrato.|
|-|

### Operação de extrato

| Essa operação deve listar todos os depósitos e saques realizados na conta. No fim da listagem deve ser exibido o saldo atual da conta.                                                                                                                                                               Os valores devem ser exibidos utilizando o formato R$ xxx.xx               exemplo: 1500.45 = R$ 1500.45|
|-|

# Hands On! Resolução do Desafio

## Objetivo Geral

_Criar um sistema bancário com as operações: sacar, depositar e visualizar extrato._ 

## Desafio

| Fomos Contratados por um grande banco para desenvolver o seu novo sistema. Esse banco deseja modernizar suas operações e para isso escolheu a linguagem Python. Para a primeira versão do sistema devemos implementar apenas 3 operações: depósito, saque e extrato.|
|-|

### Atividade concluída

      MENU = """ 
      ############# MENU #############
      [d] Depositar
      [s] Sacar
      [e] Extrato
      [q] Sair
      ################################

      """ 

      saldo = 0
      limite = 500
      extrato = ""
      total_sacado = 0
      numero_saques = 0
      LIMITE_SAQUES = 3

      while True:

        print(MENU)
        opcao = input("Digite a opção desejada: ").lower()

      #opcao = input(MENU)

        # Depositar
          # O limite de depositos é de 500 reais.
          # Se o saldo ultrapassar esse limite, não será possível depositar mais.
      
      if opcao == '1':
        valor = float(input("Digite o valor para depositar: ").replace(',','.'))

        if valor > 1:

            saldo += valor

            extrato += f"Depósito: R$ {valor:.2f}\n"

            print(f"\nDepositado com sucesso!\nSeu novo saldo é: R$ {saldo:.2f}🤑")

        else: 
            print("\nOperação falhou! O valor informado é inválido!⚠️")

    # Sacar
        # O limite de saques é de 3 unidades. Com limite máximo de R$ 500,00 por saque.
        # Se o número de saques ultrapassar esse limite, não será possível sacar mais.
        # Se o saldo ultrapassar o limite de saques diário, não será possível sacar mais.

    elif opcao == '2':
        if numero_saques >= LIMITE_SAQUES:

            print("\nVocê atingiu o limite de saques.🥲 \nPor favor, tente outra opção!")

        else:
            valor = float(input("\nDigite o valor para sacar💰: ").replace(',', '.'))

            if valor <= 0:
                print("\nOperação falhou! O valor informado é inválido!⚠️")

            elif valor > saldo:
                print("\nSaldo insuficiente.💸") 

            # excedeu o limite de saques
            elif valor > 500: 

                print("\nOperação falhou⚠️⚠️⚠️\nO valor do saque ultrapassou o limite máximo de R$ 500,00 por transação!⚠️")


            else:
                saldo -= valor
                numero_saques += 1
                total_sacado += valor
                extrato += f"Saque: -R$ {valor:.2f}\n"
                
                print(f"\nSaque efetuado com sucesso!\n💰 Seu novo saldo é: R$ {saldo:.2f}")
                
                print(f"\nTotal sacado: R$ {total_sacado:.2f}")
                
                print(f"\nVocê já realizou {numero_saques} saques.")
                
                if numero_saques >= LIMITE_SAQUES:
                
                    print("\nVocê atingiu o limite diário de saques.🥲")

                else:
                
                    print(f"\nVocê ainda pode realizar {LIMITE_SAQUES - numero_saques} saques.")

    # Extrato

    # O extrato possui um limite de 1000 unidades.


    elif opcao == '3':

        print("\n############# EXTRATO #############")

        print(f"\nSeu saldo atual é: R$ {saldo:.2f}\n")

        print("\nNão foram realizadas movimentações." if not extrato else extrato)
        
        print(f"\nTotal sacado: R$ {total_sacado:.2f}")
        
        print("\n################################")

    # Sair
    elif opcao == '0':

        print("\nObrigado por utilizar os nossos serviços!💘\nAté logo!😎\nSaindo👋...")
        break 

    # Se a opção não for um número inteiro entre 0 e 3
    else:
        print("\nOpção inválida⚠️.\nPor favor, selecione novamente a operação desejada!")

# Trabalhando com Listas em Python

##  O que iremos aprender?


| **Listas: Criação e acesso aos dados**|
|-|
>>>
|**Métodos da classe `list`**|
|-|

### Pré-requiisitos

* Python 3+
* VSCode

### Materiais de apoio

Os slides estarão disponíveis neste [LINK](https://academiapme-my.sharepoint.com/:p:/g/personal/nubia_dio_me/EVPXb3r8bPBEryfuvxp2uhABKXdIyWyufNXAjxQuOzabdQ?e=MDo5cY) 🔗
# Listas: Criação e acesso aos dados

## Criando listas 

_Listas em Python podem armazenar de maneira sequencial qualquer tipo de objeto. Podemos Criar listas utilizando o contrutor `list`, a função `range` ou colocando valores separados por vírgula dentro de colchetes. Listas são objetos mutáveis, portanto podemos alterar seus valores após a criação._ 

### Exemplo

      frutas = ["laranja", "maca", "uva"]

      frutas = []

      letras = list("python")

      numeros = list(range(10))

      carro = ["Ferrari", "F8", 4200000, 2020, 2900, "São Paulo", True]

## Acesso direto

_A lista é uma sequência, portanto podemos acessar seus dados utilizando índices. Contamos o índice de determinada sequência a partir do zero._ 

### Exemplo

      frutas = ["maçã", "laranja", "uva", "pêra"]
      frutas[0] # maçã
      frutas[2] # uva

## Índices negativos

_Sequências suportam indexação negativa. A contagem começa em -1._

### Exemplo

      frutas = ["maçã", "laranja", "uva", "pêra"]
      frutas[-1] # pêra
      frutas[-3] # laranja

## Lista aninhadas

_Listas podem armazenar todos os tipos de objetos Python, portanto podemos ter listas que armazenam outras listas. Com isso podemos criar estruturas bidimensionais (tabelas), e acessar informando os índices de linha e coluna._ 

### Exemplo

      matriz = [
      [1, "a", 2],
      ["b", 3, 4],
      [6, 5, "c"]
      ]

      matriz[0] # [1, "a", 2]
      matriz[0][0] # 1
      matriz[0][-1] #2
      matriz[-1][-1] # "c"

## Fatiamento

_Além de acessar elementos diretamente, podemos extrair um conjunto de valores de uma sequência. Para isso basta passar o índice inicial e/ou final para acessar o conjunto. Podemos ainda informar quantas posições o cursor deve "pular" no acesso._ 

### Exemplo

      lista = ["p", "y", "t", "h", "o", "n"]
      
      Lista[2:] # ["t", "h", "o", "n"] # Explicação: Começa no índice 2 e vai até o final da lista.
      
      lista[:2] # ["p", "y"] # Explicação: Vai do início da lista até o índice 2 (não incluindo o índice 2).
      
      lista[1:3] # ["y", "t"] # Explicação: Começa no índice 1 e vai até o índice 3 (não incluindo o índice 3).
      
      lista[0:3:2] # ["p","t"] # Explicação: Começa no índice 0, vai até o índice 3 (não incluindo o índice 3), e pula de 2 em 2 elementos.
      
      lista[::] # ["p", "y", "t", "h", "o", "n"] # Explicação: Pega todos os elementos da lista, do início ao fim.
      
      lista[::-1] # ["n", "o", "h", "t", "y", "p"] # Explicação: Pega todos os elementos da lista, mas na ordem inversa.

## Iterar listas

_A forma mais comum para percorrer os dados de uma lista é utilizando o comando `for`._ 

### Exemplo 

      carros = ["gol", "celta", "palio"]

      for carro in carros:
          print(carro)

## Função enumerate

_Às vezes é necessário saber qual o índice do objeto dentro do laço `for`. Para isso podemos usar a função `enumerate`._ 

### Exemplo

      carros = ["gol", "celta", "palio"]

      for indice, carro in enumerate(carros):
          print(f"{indice}: {carro}")

## Compreensão de listas 

_A compreensão de lista oferece uma sintaxe mais curta quando você deseja: criar uma nova lista com base nos valores de uma lista  existente (filtro) ou gerar uma nova lista aplicando alguma modificação nos elementos de uma lista existente._ 

### Filtro versão 1

      numeros = [1, 30, 21, 2, 9, 65, 34]
      pares = []

      for numero in numeros:
          if numero % 2 == 0:
              pares.append(numero)

O método `.append()` é usado em Python para adicionar um elemento ao final de uma lista existente. Por exemplo, se você tem uma lista `[1, 2, 3]` e usa `lista.append(4)`, a lista se torna `[1, 2, 3, 4]`¹².

Aqui está um exemplo prático:

```python
# Definindo uma lista inicial
numeros = [1, 2, 3]

# Adicionando um novo elemento ao final da lista
numeros.append(4)

# Imprimindo a lista atualizada
print(numeros)
```

Resultado:
```
[1, 2, 3, 4]
```


### Filtro versão 2

      numeros = [1, 30, 21, 2, 9, 65, 34]
      pares = [numero for numero in numeros if numero % 2 == 0]

### Modificando valores versão 1

      numeros = [1, 30, 21, 2, 9, 65, 34]
      quadrado = []

      for numero in numeros:
          quadrado.append(numero ** 2)

###  Modificando valores versão 2

      numeros = [1, 30, 21, 2, 9, 65, 34]
      quadrado = [numero ** 2 for numero in numeros]


# Métodos da classe list
### Metódo [].append

      lista = []

      lista.append(1)
      lista.append("Python")
      lista.append([40, 30, 20])

      print(lista)
      >>> [1, "Python", [40, 30, 20]]

* O método `.append()` é usado em Python para adicionar um elemento ao final de uma lista existente. Por exemplo, se você tem uma lista `[1, 2, 3]` e usa `lista.append(4)`, a lista se torna `[1, 2, 3, 4]`.

Aqui está um exemplo prático:

```python
# Definindo uma lista inicial
numeros = [1, 2, 3]

# Adicionando um novo elemento ao final da lista
numeros.append(4)

# Imprimindo a lista atualizada
print(numeros)
```

Resultado:
```
[1, 2, 3, 4]
```
## Metódo [].clear

* O método `[].clear()` em Python é usado para remover todos os elementos de uma lista, deixando-a vazia. Por exemplo, se você tem uma lista `[1, 2, 3]` e usa `lista.clear()`, a lista se torna `[]`.

Aqui está um exemplo prático:

```python
# Definindo uma lista inicial
numeros = [1, 2, 3, 4, 5]

# Limpando todos os elementos da lista
numeros.clear()

# Imprimindo a lista atualizada
print(numeros)
```

Resultado:
```
[]
```
## Metódo [].copy

* O método `[].copy()` em Python é usado para criar uma cópia superficial (shallow copy) de uma lista. Isso significa que ele cria uma nova lista que contém os mesmos elementos da lista original, mas não copia os elementos internos de forma profunda. Em outras palavras, se a lista contiver outras listas (listas aninhadas), essas listas internas não serão copiadas, apenas referenciadas.

Aqui está um exemplo prático:

```python
# Definindo uma lista inicial
numeros = [1, 2, 3, [4, 5]]

# Fazendo uma cópia superficial da lista
numeros_copia = numeros.copy()

# Modificando a lista copiada
numeros_copia[3][0] = 99

# Imprimindo as listas
print("Original:", numeros)
print("Cópia:", numeros_copia)
```

Resultado:
```
Original: [1, 2, 3, [99, 5]]
Cópia: [1, 2, 3, [99, 5]]
```

Como você pode ver, a modificação na lista copiada afetou a lista original porque a cópia foi superficial.

#### Outro exemplo:

      lista = [1, "Python", [40, 30, 20]]

      l2 = lista.copy()

      print (lista)  # [1, "Python", [40, 30, 20]]

      print(id (l2), id(lista))

      l2[0] = 2

      print(l2)
      print(lista)

      >>> # Resultado
      [1, "Python", [40, 30, 20]]
      139903141989440 139903141992704
      [2, "Python", [40, 30, 20]]
      [1, "Python", [40, 30, 20]]

## Metódo [].count

* O método `[].count()` em Python é usado para contar quantas vezes um determinado elemento aparece em uma lista. Por exemplo, se você tem uma lista `[1, 2, 2, 3, 2]` e usa `lista.count(2)`, o resultado será `3`, pois o número `2` aparece três vezes na lista⁵.

Aqui está um exemplo prático:

```python
# Definindo uma lista inicial
numeros = [1, 2, 2, 3, 2, 4, 5]

# Contando quantas vezes o número 2 aparece na lista
contagem = numeros.count(2)

# Imprimindo o resultado
print(contagem)
```

Resultado:
```
3
```
## Método [].extend

* O método `[].extend()` em Python é usado para adicionar todos os elementos de um iterável (como uma lista, tupla, ou string) ao final de uma lista existente. Diferente do método `append()`, que adiciona um único elemento, o `extend()` permite adicionar múltiplos elementos de uma vez.

Aqui está um exemplo prático:

```python
# Definindo uma lista inicial
numeros = [1, 2, 3]

# Definindo outra lista para adicionar
novos_numeros = [4, 5, 6]

# Usando extend para adicionar todos os elementos de novos_numeros à lista numeros
numeros.extend(novos_numeros)

# Imprimindo a lista atualizada
print(numeros)
```

Resultado:
```
[1, 2, 3, 4, 5, 6]
```

## Metódo [].index

* O método `[].index()` em Python é usado para encontrar o índice da primeira ocorrência de um elemento específico em uma lista. Se o elemento não estiver presente na lista, ele gera um erro `ValueError`.

Aqui está um exemplo prático:

```python
# Definindo uma lista inicial
frutas = ['maçã', 'banana', 'cereja', 'banana']

# Encontrando o índice da primeira ocorrência de 'banana'
indice = frutas.index('banana')

# Imprimindo o índice encontrado
print(indice)
```

Resultado:
```
1
```

Você também pode especificar um intervalo de busca usando os parâmetros opcionais `start` e `end`:

```python
# Encontrando o índice da primeira ocorrência de 'banana' após o índice 2
indice = frutas.index('banana', 2)

# Imprimindo o índice encontrado
print(indice)
```

Resultado:
```
3
```

## Metódo [].pop

* O método `[].pop()` em Python é usado para remover e retornar o último elemento de uma lista. Se você fornecer um índice opcional, ele removerá e retornará o elemento na posição especificada.

Aqui está um exemplo prático:

```python
# Definindo uma lista inicial
frutas = ['maçã', 'banana', 'cereja']

# Removendo e retornando o último elemento
ultima_fruta = frutas.pop()

# Imprimindo o elemento removido e a lista atualizada
print(ultima_fruta)  # Output: cereja
print(frutas)        # Output: ['maçã', 'banana']
```

Você também pode especificar um índice:

```python
# Removendo e retornando o elemento no índice 1
fruta_indice_1 = frutas.pop(1)

# Imprimindo o elemento removido e a lista atualizada
print(fruta_indice_1)  # Output: banana
print(frutas)          # Output: ['maçã']
```
#### Outro exemplo

      linguagens = ["python", "js", "c", "java", "csharp"]

      linguagens.pop() # csharp
      linguagens.pop() # java
      linguagens.pop() # c
      linguagens.pop(0) # python


## Metódo [].remove 

* O método `[].remove()` em Python é usado para remover a primeira ocorrência de um valor específico em uma lista. Se o valor não estiver presente na lista, ele gera um erro `ValueError`.

Aqui está um exemplo prático:

```python
# Definindo uma lista inicial
frutas = ['maçã', 'banana', 'cereja', 'banana']

# Removendo a primeira ocorrência de 'banana'
frutas.remove('banana')

# Imprimindo a lista atualizada
print(frutas)
```

Resultado:
```
['maçã', 'cereja', 'banana']
```

## Metódo [].reverse

* O método `[].reverse()` em Python é usado para inverter a ordem dos elementos de uma lista, modificando a lista original no local. Isso significa que a lista será alterada diretamente, sem criar uma nova lista.

Aqui está um exemplo prático:

```python
# Definindo uma lista inicial
numeros = [1, 2, 3, 4, 5]

# Invertendo a ordem dos elementos da lista
numeros.reverse()

# Imprimindo a lista atualizada
print(numeros)
```

Resultado:
```
[5, 4, 3, 2, 1]
```

## Metódo [].sort

* O método `[].sort()` em Python é usado para ordenar os elementos de uma lista no local, ou seja, ele modifica a lista original sem criar uma nova. Por padrão, ele ordena os elementos em ordem crescente. Você também pode usar o parâmetro `reverse=True` para ordenar em ordem decrescente.

Aqui está um exemplo prático:

```python
# Definindo uma lista inicial
numeros = [5, 2, 9, 1, 5, 6]

# Ordenando a lista em ordem crescente
numeros.sort()

# Imprimindo a lista ordenada
print(numeros)
```

Resultado:
```
[1, 2, 5, 5, 6, 9]
```

Para ordenar em ordem decrescente:

```python
# Ordenando a lista em ordem decrescente
numeros.sort(reverse=True)

# Imprimindo a lista ordenada
print(numeros)
```

Resultado:
```
[9, 6, 5, 5, 2, 1]
```

* Você também pode usar o parâmetro `key` para personalizar a ordenação. Por exemplo, para ordenar uma lista de strings ignorando maiúsculas e minúsculas:

```python
# Definindo uma lista de strings
palavras = ['banana', 'Maçã', 'cereja']

# Ordenando a lista ignorando maiúsculas e minúsculas
palavras.sort(key=str.lower)

# Imprimindo a lista ordenada
print(palavras)
```

Resultado:
```
['banana', 'cereja', 'Maçã']
```

#### Outros exemplos

      linguagens = ["python", "js", "c", "java", "csharp"]
      linguagens.sort() # ["c", "csharp", "java", "js", "python"]

      linguagens = ["python", "js", "c", "java", "csharp"]
      linguagens.sort(reverse=True) # ["python", "js", "java", "csharp", "c"]

      linguagens = ["python", "js", "c", "java", "csharp"]
      linguagens.sort(key=lambda x: len(x)) # ["c", "js", "java", "python", "csharp"] # `lambda` é uma função anônima e o `x` é o argumento (que é cada item da lista)

      linguagens = ["python", "js", "c", "java", "csharp"]
      linguagens.sort(key=lambda x: len(x), reverse=True) # ["python", "csharp", "java", "js", "c"]



## Metódo len()

* A função `len()` em Python é usada para retornar o comprimento (ou número de itens) de um objeto. Esse objeto pode ser uma lista, tupla, string, dicionário, entre outros.

Aqui está um exemplo prático:

```python
# Definindo uma lista inicial
numeros = [1, 2, 3, 4, 5]

# Usando len() para obter o comprimento da lista
comprimento = len(numeros)

# Imprimindo o comprimento
print(comprimento)
```

Resultado:
```
5
```

Você também pode usar `len()` com outros tipos de dados, como strings e dicionários:

```python
# Usando len() com uma string
texto = "Olá, mundo!"
comprimento_texto = len(texto)
print(comprimento_texto)  # Output: 11

# Usando len() com um dicionário
dicionario = {'a': 1, 'b': 2, 'c': 3}
comprimento_dicionario = len(dicionario)
print(comprimento_dicionario)  # Output: 3
```

## Metódo sorted()

* A função `sorted()` em Python é usada para ordenar iteráveis, como listas, tuplas e conjuntos. Diferente do método `sort()`, que modifica a lista original, `sorted()` retorna uma nova lista com os elementos ordenados.

Aqui está um exemplo prático:

```python
# Definindo uma lista inicial
numeros = [5, 2, 9, 1, 5, 6]

# Usando sorted() para ordenar a lista em ordem crescente
numeros_ordenados = sorted(numeros)

# Imprimindo a lista original e a lista ordenada
print("Original:", numeros)
print("Ordenada:", numeros_ordenados)
```

Resultado:
```
Original: [5, 2, 9, 1, 5, 6]
Ordenada: [1, 2, 5, 5, 6, 9]
```

Você também pode usar o parâmetro `reverse=True` para ordenar em ordem decrescente:

```python
# Ordenando a lista em ordem decrescente
numeros_ordenados_desc = sorted(numeros, reverse=True)

# Imprimindo a lista ordenada em ordem decrescente
print("Ordenada (decrescente):", numeros_ordenados_desc)
```

Resultado:
```
Ordenada (decrescente): [9, 6, 5, 5, 2, 1]
```

Além disso, você pode usar o parâmetro `key` para personalizar a ordenação. Por exemplo, para ordenar uma lista de strings ignorando maiúsculas e minúsculas:

```python
# Definindo uma lista de strings
palavras = ['banana', 'Maçã', 'cereja']

# Ordenando a lista ignorando maiúsculas e minúsculas
palavras_ordenadas = sorted(palavras, key=str.lower)

# Imprimindo a lista ordenada
print("Ordenada:", palavras_ordenadas)
```

Resultado:
```
Ordenada: ['banana', 'cereja', 'Maçã']
```

# Conhecendo Tuplas em Python

## Objetivo Geral

_Entender o funcionamento da estrutura de dados tupla._ 

## Pré-requisitos

* Python 3+
* VSCode

## Percursos

|**Etapa 1**|
|-|

* Criação e acesso aos dados 

|**Etapa 2**|
|-|

* Métodos da classe `tuple`

## Materiais de apoio

[Slides do material - _clique aqui_](https://academiapme-my.sharepoint.com/:p:/g/personal/nubia_dio_me/ER_pCeDKskRCvfnbSsQtZ7gBnX3Nk7I0_jotj52VPltL3Q?e=BOheig) 🔗 
# Criação e acesso aos dados

## Criando tuplas

_Tuplas são estruturas de dados muito parecidas com as listas, a principal diferença é que tuplas são imutáveis enquanto listas são mutáveis (*ou seja, uma vez criadas, seus valores não podem ser alterados*). Podemos criar tuplas através da classe `tuple`, ou colocando valores separados por vírgula de parenteses._ 

### Quando Usar Tuplas:
Dados Constantes: Quando você tem um conjunto de valores que não devem ser alterados.
Desempenho: Tuplas podem ser mais rápidas que listas para acessar elementos.
Chaves de Dicionário: Podem ser usadas como chaves em dicionários, pois são imutáveis.

#### Exemplo:

      frutas = ("laranja", "pera", "uva",)

      letras = tuple("python")

      numeros = tuple([1, 2, 3, 4])

      pais = ("Brasil",) 

## Acesso direto

_A tupla é uma sequência, portanto podemos acessar seus dados utilizando índices. Contamos o índice de determinada sequência a partir do zero._ 

#### Exemplo:

      frutas = ("maçã", "laranja", "uva", "pêra",)
      frutas[0] # maçã
      frutas[2] # uva

## Índices negativos

_sequências suportam indexação negativa. A contagem começa em -1._ 

#### Exemplo:

      frutas = ("maçã", "laranja", "uva", "pêra",)
      frutas[-1] # pêra
      frutas[-3] # laranja

## Tuplas aninhadas

_Tuplas podem armazenar todos os tipos de objetos Python, portanto podemos ter tuplas que armazenam outras tuplas. Com isso podemos criar estruturas bidimensionais (tabelas), e acessar informando os índices de linha e coluna._ 

#### Exemplo:

        matriz = (
          (1, "a", 2),
          ("b", 3, 4),
          (6, 5, "c"),
        )

        matriz[0] # (1, "a", 2)
        matriz[0][0] # 1
        matriz[0][-1] # 2
        matriz[-1][-1] # "c"

## Fatiamento

_Além de acessar elementos diretamente, podemos extrair um conjunto de valores de uma sequência. Para isso basta passar o índice inicial e/ou final para acessar o conjunto. Podemos ainda informar quantas posições o cursor deve "pular" no acesso._ 

#### Exemplo:

      tupla = ("p", "y", "t", "h", "o", "n")

      tupla[2:] # ("t", "h", "o", "n")
      tupla[:2] # ("p", "y")
      tupla[1:3] # ("y", "t")
      tupla[0:3:2] # ("p", "t")
      tupla[::] # ("p", "y", "t", "h", "o", "n")
      tupla[::-1] # ("n", "o", "h", "t", "y", "p")

## Iterar Tuplas

_A forma mais comum para percorrer os dados de uma tupla é utilizando o comando `for`._ 

#### Exemplo:

      carros = ("gol", "celta", "palio",)

      for carro in carros:
          print(carro)

## Função enumerate

_Às vezes é necessáro saber qual o índice do objeto dentro do laço `for`. Para isso podemos usar a função `enumerate`._ 

#### Exemplo:

      carros = ("gol", "celta", "palio",)

      for indice, carro in enumerate(carros):
          print(f"{indice}: {carro}")


# Métodos da classe `tuple`

## Método ().count

* O método `count()` é uma função integrada em várias linguagens de programação, como Python, que é usada para contar o número de ocorrências de um determinado valor em uma lista ou string.

### Exemplo em Python:
```python
# Contando a ocorrência de um valor em uma lista
frutas = ['maçã', 'banana', 'cereja', 'maçã', 'cereja', 'maçã']
contagem_maca = frutas.count('maçã')
print(contagem_maca)  # Saída: 3

# Contando a ocorrência de um valor em uma string
texto = "Olá, mundo! Olá, Python!"
contagem_ola = texto.count('Olá')
print(contagem_ola)  # Saída: 2
```

No exemplo acima, `frutas.count('maçã')` retorna o número de vezes que 'maçã' aparece na lista `frutas`, e `texto.count('Olá')` retorna o número de vezes que 'Olá' aparece na string `texto`¹².

#### Exemplo:

      cores = ('vermelho', 'azul', 'verde', 'azul',)

      cores.count('vermelho') # 1
      cores.count('azul') # 2
      cores.count('verde') # 1

## Método ().index

* O método `index()` é uma função útil em Python para encontrar a posição de um item específico em uma lista. Ele retorna o índice da primeira ocorrência do valor especificado. Se o valor não for encontrado, ele gera um erro `ValueError`.

### Sintaxe:
```python
lista.index(item, inicio, fim)
```
- **item**: O valor que você está procurando.
- **inicio** (opcional): O índice onde a busca deve começar.
- **fim** (opcional): O índice onde a busca deve terminar.

### Exemplo:
```python
# Exemplo básico
nomes = ['Ana', 'Carlos', 'Beatriz', 'Ana']
indice_ana = nomes.index('Ana')
print(indice_ana)  # Saída: 0

# Usando os parâmetros inicio e fim
indice_ana_segunda = nomes.index('Ana', 1)
print(indice_ana_segunda)  # Saída: 3
```

No primeiro exemplo, `nomes.index('Ana')` retorna `0` porque 'Ana' aparece pela primeira vez no índice 0. No segundo exemplo, `nomes.index('Ana', 1)` começa a busca a partir do índice 1, retornando `3`.


## Método len()

* O método `len()` em Python é uma função interna que retorna o comprimento (ou número de itens) de um objeto. Ele pode ser usado com vários tipos de dados, como listas, strings, tuplas, dicionários, conjuntos, entre outros.

### Sintaxe:
```python
len(objeto)
```
- **objeto**: O objeto cujo comprimento você deseja calcular.

### Exemplos:
```python
# Exemplo com uma lista
frutas = ['maçã', 'banana', 'cereja']
print(len(frutas))  # Saída: 3

# Exemplo com uma string
texto = "Olá, mundo!"
print(len(texto))  # Saída: 11

# Exemplo com um dicionário
dicionario = {'nome': 'Ana', 'idade': 25}
print(len(dicionario))  # Saída: 2
```

O método `len()` é muito útil para verificar o tamanho de coleções e sequências em Python.


# Explorando Conjuntos em Python

## Objetivo Geral

_Entender o funcionamento da estrutura de dados `set`._

## Pré-requisitos

* Python 3+
* VSCode

## Percurso

|**Etapa 1**|
|-|

* Como criar conjuntos 

|**Etapa 2**|
|-|

* Métodos da classe `set`

## Materiais de apoio

Os slides estarão disponíveis [_aqui_](https://academiapme-my.sharepoint.com/:p:/g/personal/nubia_dio_me/EWxVjZ3N_-5OmGYkDrdEQkoB0NuroEV5wvMavMOA9-nI2Q?e=Nr7pE0) 🔗
# Como criar conjuntos

## Criando `sets`

_Um `set` é uma coleção que não possui objetos repetidos, usamos sets para representar conjuntos matemáticos ou eliminar itens duplicados de um iterável._ 

#### Exemplo:

```
set([1, 2, 3, 1, 3, 4]) # {1, 2, 3, 4}

set("abacaxi") # {"b", "a", "c", "x", "i"}

set(("palio", "gol", "celta", "palio")) # {"gol", "celta", "palio"}

```

## Acessando os dados 

_Conjuntos em Python não suportam indexação e nem fatiamento, caso queira acessar os seus valores é necessário converter o conjunto para lista._ 

#### Exemplo:

```
numeros = {1, 2, 3, 2}

numeros = list(numeros) # Converte para lista 

print(numeros[0])
```
## Iterar conjuntos

_A forma mais comum para percorrer os dados de um conjunto é utilizando o comando `for`._ 

#### Exemplo:

```
carros = {'gol', 'celta', 'palio'}

for carro in carros:
    print(carro)
```

## Função enumerate

_Às vezes é necessário saber qual o índice do objeto dentro do laço `for`. Para isso podemos usar a função `enumerate`._

#### Exemplo:

```
carros = {'gol', 'celta', 'palio'}

for indice, carro in enumerate(carros):
    print(f"{indice}: {carro})
```

## Método {}.union

* O método `union()` em Python é utilizado para unir dois ou mais conjuntos, retornando um novo conjunto que contém todos os elementos dos conjuntos originais, sem duplicatas. Você pode usar tanto o método `union()` quanto o operador `|` para realizar essa operação.

Aqui está um exemplo de como usar o método `union()`:

```python
# Definindo dois conjuntos
conjunto_1 = {1, 2, 3, 4}
conjunto_2 = {3, 4, 5, 6}

# Usando o método union()
resultado = conjunto_1.union(conjunto_2)
print(resultado)  # Saída: {1, 2, 3, 4, 5, 6}

# Usando o operador |
resultado = conjunto_1 | conjunto_2
print(resultado)  # Saída: {1, 2, 3, 4, 5, 6}
```

Ambos os métodos produzem o mesmo resultado, unindo os elementos dos dois conjuntos sem repetir valores.

## Método {}.intersection

* O método `intersection()` em Python é utilizado para encontrar a interseção de dois ou mais conjuntos, retornando um novo conjunto que contém apenas os elementos comuns a todos os conjuntos envolvidos. Você também pode usar o operador `&` para realizar essa operação.

Aqui está um exemplo de como usar o método `intersection()`:

```python
# Definindo dois conjuntos
conjunto_1 = {1, 2, 3, 4}
conjunto_2 = {3, 4, 5, 6}

# Usando o método intersection()
resultado = conjunto_1.intersection(conjunto_2)
print(resultado)  # Saída: {3, 4}

# Usando o operador &
resultado = conjunto_1 & conjunto_2
print(resultado)  # Saída: {3, 4}
```

Ambos os métodos produzem o mesmo resultado, retornando os elementos que são comuns aos dois conjuntos.

## Método {}.difference

* O método `difference()` em Python é utilizado para encontrar a diferença entre dois conjuntos, retornando um novo conjunto que contém os elementos que estão no primeiro conjunto, mas não no segundo. Você também pode usar o operador `-` para realizar essa operação.

Aqui está um exemplo de como usar o método `difference()`:

```python
# Definindo dois conjuntos
conjunto_1 = {1, 2, 3, 4}
conjunto_2 = {3, 4, 5, 6}

# Usando o método difference()
resultado = conjunto_1.difference(conjunto_2)
print(resultado)  # Saída: {1, 2}

# Usando o operador -
resultado = conjunto_1 - conjunto_2
print(resultado)  # Saída: {1, 2}
```

Ambos os métodos produzem o mesmo resultado, retornando os elementos que estão no primeiro conjunto, mas não no segundo.

## Método {}.symmetri_difference

* O método `symmetric_difference()` em Python é utilizado para encontrar a diferença simétrica entre dois conjuntos. Ele retorna um novo conjunto que contém os elementos que estão em um dos conjuntos, mas não em ambos. Você também pode usar o operador `^` para realizar essa operação.

Aqui está um exemplo de como usar o método `symmetric_difference()`:

```python
# Definindo dois conjuntos
conjunto_1 = {1, 2, 3, 4}
conjunto_2 = {3, 4, 5, 6}

# Usando o método symmetric_difference()
resultado = conjunto_1.symmetric_difference(conjunto_2)
print(resultado)  # Saída: {1, 2, 5, 6}

# Usando o operador ^
resultado = conjunto_1 ^ conjunto_2
print(resultado)  # Saída: {1, 2, 5, 6}
```

Ambos os métodos produzem o mesmo resultado, retornando os elementos que estão em um dos conjuntos, mas não em ambos.

## Método {}.issubset

* O método `issubset()` em Python é utilizado para verificar se todos os elementos de um conjunto estão contidos em outro conjunto. Ele retorna `True` se o conjunto é um subconjunto do outro, e `False` caso contrário. Você também pode usar o operador `<=` para realizar essa verificação.

Aqui está um exemplo de como usar o método `issubset()`:

```python
# Definindo dois conjuntos
conjunto_1 = {1, 2, 3}
conjunto_2 = {1, 2, 3, 4, 5}

# Usando o método issubset()
resultado = conjunto_1.issubset(conjunto_2)
print(resultado)  # Saída: True

# Usando o operador <=
resultado = conjunto_1 <= conjunto_2
print(resultado)  # Saída: True
```

Ambos os métodos produzem o mesmo resultado, verificando se todos os elementos do primeiro conjunto estão presentes no segundo.

## Método {}.issuperset

* O método `issuperset()` em Python é utilizado para verificar se todos os elementos de um conjunto estão contidos em outro conjunto. Ele retorna `True` se o conjunto é um superconjunto do outro, e `False` caso contrário. Você também pode usar o operador `>=` para realizar essa verificação.

Aqui está um exemplo de como usar o método `issuperset()`:

```python
# Definindo dois conjuntos
conjunto_1 = {1, 2, 3, 4, 5}
conjunto_2 = {1, 2, 3}

# Usando o método issuperset()
resultado = conjunto_1.issuperset(conjunto_2)
print(resultado)  # Saída: True

# Usando o operador >=
resultado = conjunto_1 >= conjunto_2
print(resultado)  # Saída: True
```

Ambos os métodos produzem o mesmo resultado, verificando se todos os elementos do segundo conjunto estão presentes no primeiro.

## Método {}.isdisjoint

* O método `isdisjoint()` em Python é utilizado para verificar se dois conjuntos são disjuntos, ou seja, se não possuem elementos em comum. Ele retorna `True` se não houver elementos comuns entre os conjuntos, e `False` caso contrário.

Aqui está um exemplo de como usar o método `isdisjoint()`:

```python
# Definindo dois conjuntos
conjunto_1 = {1, 2, 3}
conjunto_2 = {4, 5, 6}

# Usando o método isdisjoint()
resultado = conjunto_1.isdisjoint(conjunto_2)
print(resultado)  # Saída: True

# Outro exemplo com conjuntos que têm elementos em comum
conjunto_3 = {3, 4, 5}
resultado = conjunto1.isdisjoint(conjunto_3)
print(resultado)  # Saída: False
```

O método `isdisjoint()` também pode ser usado com outros iteráveis, como listas ou tuplas, pois ele converte automaticamente esses iteráveis em conjuntos antes de realizar a verificação.

## Método {}.add

* O método `add()` em Python é utilizado para adicionar um único elemento a um conjunto. Se o elemento já estiver presente no conjunto, ele não será adicionado novamente, pois conjuntos não permitem duplicatas.

Aqui está um exemplo de como usar o método `add()`:

```python
# Definindo um conjunto
conjunto = {1, 2, 3}

# Usando o método add() para adicionar um elemento
conjunto.add(4)
print(conjunto)  # Saída: {1, 2, 3, 4}

# Tentando adicionar um elemento que já está no conjunto
conjunto.add(3)
print(conjunto)  # Saída: {1, 2, 3, 4}
```

Como você pode ver, o método `add()` adiciona o elemento ao conjunto apenas se ele ainda não estiver presente.

## Método {}.clear

* O método `clear()` em Python é utilizado para remover todos os elementos de um conjunto, deixando-o vazio. Este método modifica o conjunto original.

Aqui está um exemplo de como usar o método `clear()`:

```python
# Definindo um conjunto
conjunto = {1, 2, 3, 4}

# Usando o método clear() para remover todos os elementos
conjunto.clear()
print(conjunto)  # Saída: set()
```

Após a execução do método `clear()`, o conjunto ficará vazio.

## Método {}.discard

* O método `discard()` em Python é utilizado para remover um elemento específico de um conjunto, se esse elemento estiver presente. Se o elemento não estiver presente, o método não faz nada e não gera nenhum erro ou exceção.

Aqui está um exemplo de como usar o método `discard()`:

```python
# Definindo um conjunto
conjunto = {1, 2, 3, 4}

# Usando o método discard() para remover um elemento
conjunto.discard(3)
print(conjunto)  # Saída: {1, 2, 4}

# Tentando remover um elemento que não está no conjunto
conjunto.discard(5)
print(conjunto)  # Saída: {1, 2, 4}
```

Como você pode ver, o método `discard()` remove o elemento especificado se ele estiver presente no conjunto, e não faz nada se o elemento não estiver presente.

## Método {}.pop

* O método `pop()` em Python é utilizado para remover e retornar um elemento específico de um conjunto. Diferente do método `discard()`, o `pop()` remove um elemento arbitrário do conjunto, pois conjuntos não mantêm uma ordem específica. Se o conjunto estiver vazio, ele gera um erro `KeyError`.

Aqui está um exemplo de como usar o método `pop()`:

```python
# Definindo um conjunto
conjunto = {1, 2, 3, 4}

# Usando o método pop() para remover um elemento
elemento_removido = conjunto.pop()
print(elemento_removido)  # Saída: (um dos elementos do conjunto, por exemplo, 1)
print(conjunto)  # Saída: o conjunto sem o elemento removido, por exemplo, {2, 3, 4}

# Tentando usar pop() em um conjunto vazio
conjunto_vazio = set()
try:
    conjunto_vazio.pop()
except KeyError as e:
    print("Erro:", e)  # Saída: Erro: 'pop from an empty set'
```

O método `pop()` é útil quando você precisa remover e obter um elemento de um conjunto, mas não se importa com qual elemento será removido.

## Método {}.remove

* O método `remove()` em Python é utilizado para remover a primeira ocorrência de um elemento específico de uma lista. Se o elemento não estiver presente na lista, ele gera um erro `ValueError`.

Aqui está um exemplo de como usar o método `remove()`:

```python
# Definindo uma lista
lista = [1, 2, 3, 4, 3, 5]

# Usando o método remove() para remover a primeira ocorrência do elemento 3
lista.remove(3)
print(lista)  # Saída: [1, 2, 4, 3, 5]

# Tentando remover um elemento que não está na lista
try:
    lista.remove(6)
except ValueError as e:
    print("Erro:", e)  # Saída: Erro: list.remove(x): x not in list
```

O método `remove()` é útil quando você precisa remover um elemento específico de uma lista, mas lembre-se de que ele só remove a primeira ocorrência desse elemento.

## Método {}.len

* O método `len()` em Python é utilizado para obter o número de elementos em um objeto, como listas, tuplas, strings, dicionários e conjuntos. Ele retorna um valor inteiro que representa a quantidade de itens no objeto.

Aqui está um exemplo de como usar o método `len()` com diferentes tipos de objetos:

```python
# Usando len() com uma lista
lista = [1, 2, 3, 4]
print(len(lista))  # Saída: 4

# Usando len() com uma tupla
tupla = (1, 2, 3, 4)
print(len(tupla))  # Saída: 4

# Usando len() com uma string
string = "Python"
print(len(string))  # Saída: 6

# Usando len() com um dicionário
dicionario = {'a': 1, 'b': 2, 'c': 3}
print(len(dicionario))  # Saída: 3

# Usando len() com um conjunto
conjunto = {1, 2, 3, 4}
print(len(conjunto))  # Saída: 4
```

O método `len()` é bastante versátil e pode ser aplicado a qualquer objeto que suporte a operação de contagem de elementos.

## Método in

* O operador `in` em Python é utilizado para verificar se um elemento está presente em uma sequência, como uma lista, tupla, string, conjunto ou dicionário. Ele retorna `True` se o elemento estiver presente e `False` caso contrário.

Aqui estão alguns exemplos de como usar o operador `in`:

```python
# Usando in com uma lista
lista = [1, 2, 3, 4]
print(2 in lista)  # Saída: True
print(5 in lista)  # Saída: False

# Usando in com uma tupla
tupla = (1, 2, 3, 4)
print(3 in tupla)  # Saída: True
print(6 in tupla)  # Saída: False

# Usando in com uma string
string = "Python"
print('P' in string)  # Saída: True
print('p' in string)  # Saída: False

# Usando in com um conjunto
conjunto = {1, 2, 3, 4}
print(3 in conjunto)  # Saída: True
print(5 in conjunto)  # Saída: False

# Usando in com um dicionário (verifica se a chave está presente)
dicionario = {'a': 1, 'b': 2, 'c': 3}
print('a' in dicionario)  # Saída: True
print(1 in dicionario)  # Saída: False
```

O operador `in` é bastante versátil e pode ser usado com diferentes tipos de objetos para verificar a presença de elementos.
# Aprendendo a utilizar Dicionários em Python

## Objetivo Geral

_Entender o funcionamento da estrutura de dados `set`._

## Pré-requisitos

* Python 3+
* VSCode

## Percurso

|**Etapa 1**|
|-|

* **Dicionários: Criação e acesso aos dados** 

|**Etapa 2**|
|-|

* **Métodos da classe `dict`**

## Materiais de apoio

Os slides estarão disponíveis [_aqui_](https://academiapme-my.sharepoint.com/:p:/g/personal/nubia_dio_me/EebIipXNLf9GsduivQenMpUBtoohPY2ITXh1HnkB0wa2dg?e=dOZp1h) 🔗
# Dicionários: Criação e acesso aos dados

## Criando dicionários 

_Um dicionário é um conjunto não-ordenado de pares chave:valor, onde as chaves são únicas em uma dada instância do dicionário. Dicionários são delimitados por chaves: {}, e contém uma lista de pares chave:valor separada por vírgulas.

#### Exemplo:

```Python
pessoa = {'nome': 'Álisson', 'idade': 30}

pessoa = dict(nome='Álisson', idade=30)

pessoa['telefone'] = '3333-4321' # {'nome: 'Álisson', 'idade'=30, 'telefone': '3333-4321'}
```

## Acesso aos dados 

_Os dados são acessados e modificados através da chave._ 

#### Exemplo:

```Python
dados = {'nome': 'Álisson', ''idade': 30, 'telefone': '3333-4321'}

dados['nome'] # 'Álisson'
dados['idade'] # 30
dados['telefone'] # '3333-4321'

dados['nome'] = 'Maria'
dados['idade'] = 19
dados['telefone'] = '99876-5432'

dados # {'nome': 'Maria', 'idade': 19, 'telefone': '99876-5432'}
```
## Dicionários aninhados 

_Dicionários podem armazenar qualquer tipo de objeto Python como valor, desde que a chave para esse valor seja um objeto imutável como (strings e números)._ 

```
contatos = {
  'alisson@email.com': {'nome': 'Alisson', 'telefone': '3333-4321'},
  'maria@email.com': {'nome': 'Maria', 'telefone': '3333-5432'},
  'vitoria@email.com': {'nome': 'Vitoria', 'telefone': '3333-6543'},
  'lucky@email.com': {'nome': 'Lucky', 'telefone': '3333-7654', 'extrair': {'a': 1}},

}

telefone = contatos['maria@email.com']['telefone'] # '3333-5432'
print(telefone)

extra = contatos['lucky@email.com']['extra']['a']
print(extra) 
>>> 3333-7654 
>>> 1
```

## Iterar dicionários 

_A forma mais comum para percorrer os dados de um dicionário é utilizando o comando `for`._ 

#### Exemplo:

```
for chave in contatos: 
    print(chave, contatos[chave])

for chave, valor in contatos.items():
    print(chave, valor)

# 'alisson@email.com': {'nome': 'Alisson', 'telefone': '3333-4321'}
#  'maria@email.com': {'nome': 'Maria', 'telefone': '3333-5432'}
#  'vitoria@email.com': {'nome': 'Vitoria', 'telefone': '3333-6543'}
#  'lucky@email.com': {'nome': 'Lucky', 'telefone': '3333-7654'}
```


# Métodos da classe `dict`

## Método clear()

* O método `clear()` em Python é usado para remover todos os elementos de um objeto mutável, como uma lista, um dicionário ou um conjunto. Este método modifica o objeto original, deixando-o vazio.

#### Aqui está um exemplo de como usá-lo:

```python
# Usando clear() em uma lista
minha_lista = [1, 2, 3, 4, 5]
minha_lista.clear()
print(minha_lista)  # Saída: []

# Usando clear() em um dicionário
meu_dict = {"a": 1, "b": 2, "c": 3}
meu_dict.clear()
print(meu_dict)  # Saída: {}

# Usando clear() em um conjunto
meu_conjunto = {1, 2, 3, 4, 5}
meu_conjunto.clear()
print(meu_conjunto)  # Saída: set()
```
#### Outro exemplo:
```
contatos = {
  'alisson@email.com': {'nome': 'Alisson', 'telefone': '3333-4321'},
  'maria@email.com': {'nome': 'Maria', 'telefone': '3333-5432'},
  'vitoria@email.com': {'nome': 'Vitoria', 'telefone': '3333-6543'},
  'lucky@email.com': {'nome': 'Lucky', 'telefone': '3333-7654', 'extrair': {'a': 1}},

}

contatos.clear()
contatos # {}
```

O método `clear()` não aceita parâmetros e não retorna nenhum valor.

## Método copy.()

* O método `copy()` em Python é usado para criar uma cópia superficial de um objeto mutável, como uma lista, um dicionário ou um conjunto. Aqui estão alguns exemplos de como utilizá-lo:

```python
# Usando copy() em uma lista
import copy

minha_lista = [1, 2, 3, 4, 5]
minha_lista_copia = minha_lista.copy()
print(minha_lista_copia)  # Saída: [1, 2, 3, 4, 5]

# Usando copy() em um dicionário
meu_dict = {"a": 1, "b": 2, "c": 3}
meu_dict_copia = meu_dict.copy()
print(meu_dict_copia)  # Saída: {'a': 1, 'b': 2, 'c': 3}

# Usando copy() em um conjunto
meu_conjunto = {1, 2, 3, 4, 5}
meu_conjunto_copia = meu_conjunto.copy()
print(meu_conjunto_copia)  # Saída: {1, 2, 3, 4, 5}
```

Para cópias mais profundas, onde objetos aninhados também são copiados, você pode usar o módulo `copy` do Python:

```python
import copy

# Usando deepcopy() para cópia profunda
minha_lista_aninhada = [[1, 2, 3], [4, 5, 6]]
minha_lista_aninhada_copia = copy.deepcopy(minha_lista_aninhada)
print(minha_lista_aninhada_copia)  # Saída: [[1, 2, 3], [4, 5, 6]]
```

#### Outro exemplo:

```
contatos = {
  'alisson@gmail.com": {'nome': 'Álisson', 'telefone': '3333-0432'}
}

copia = contatos.copy()
copia['alisson@gmail.com'] = {'nome': 'Aly'}

contatos['alisson@gmail.com'] = {'nome': 'Aly'} # {'nome': 'Alisson', 'telefone': '3333-0432'}
copia['alisson@gmail.com'] # {'nome': 'Aly'}
```

## Método fromkeys()

* O método `fromkeys()` em Python é usado para criar um novo dicionário a partir de uma sequência de chaves, atribuindo a todas elas o mesmo valor. A sintaxe é a seguinte:

```python
novo_dict = dict.fromkeys(chaves, valor)
```

- **chaves**: uma sequência (como uma lista ou uma tupla) que contém as chaves para o novo dicionário.
- **valor**: o valor que será atribuído a todas as chaves. Se não for especificado, o valor padrão será `None`.

Aqui estão alguns exemplos:

```python
# Criando um dicionário com valores padrão None
chaves = ['a', 'b', 'c']
novo_dict = dict.fromkeys(chaves)
print(novo_dict)  # Saída: {'a': None, 'b': None, 'c': None}

# Criando um dicionário com um valor específico
valor = 0
novo_dict = dict.fromkeys(chaves, valor)
print(novo_dict)  # Saída: {'a': 0, 'b': 0, 'c': 0}
```

#### Outro exemplo:

```
dict.fromkeys(['nome', 'telefone']) # {'nome', 'telefone': None}

dict.fromkeys(['nome', 'telefone'], 'vazio') # {'nome': 'vazio', 'telefone': 'vazio'}
```

Este método é útil quando você precisa inicializar um dicionário com um conjunto fixo de chaves e um valor padrão.

## Método get()

* O método `get()` em Python é usado para acessar o valor de uma chave específica em um dicionário. A principal vantagem de usar `get()` em vez de acessar diretamente a chave é que ele permite especificar um valor padrão a ser retornado caso a chave não exista no dicionário, evitando assim erros.

A sintaxe do método `get()` é:

```python
valor = dicionario.get(chave, valor_padrao)
```

- **chave**: a chave cujo valor você deseja obter.
- **valor_padrao** (opcional): o valor a ser retornado se a chave não for encontrada. Se não for especificado, o valor padrão será `None`.

Aqui estão alguns exemplos:

```python
# Exemplo básico de uso do get()
meu_dict = {"a": 1, "b": 2, "c": 3}

# Acessando uma chave existente
valor_a = meu_dict.get("a")
print(valor_a)  # Saída: 1

# Acessando uma chave inexistente sem valor padrão
valor_d = meu_dict.get("d")
print(valor_d)  # Saída: None

# Acessando uma chave inexistente com valor padrão
valor_d_com_padrao = meu_dict.get("d", 0)
print(valor_d_com_padrao)  # Saída: 0
```

#### Outro exemplo:

```
contatos = {
  'alisson@gmail.com': {'nome': 'Alisson', 'telefone': '3333-0432'}
}

contatos['chave'] # KeyError

contatos.get('chave') # None
contatos.get('chave', {}) # {}
contatos.get('alisson@gmail.com', {}) #{'alisson@gmail.com': {'nome': 'Alisson', 'telefone': '3333-0432'}}
```

O método `get()` é especialmente útil quando você não tem certeza se uma chave está presente no dicionário e quer evitar erros de chave ausente.

## Método items()

* O método `items()` em Python é usado para retornar uma visão iterável dos pares chave-valor de um dicionário. Cada item é retornado como uma tupla contendo a chave e o valor correspondentes. A sintaxe é:

```python
dicionario.items()
```

Aqui estão alguns exemplos de como usar o método `items()`:

```python
# Exemplo básico de uso do items()
meu_dict = {"a": 1, "b": 2, "c": 3}

# Iterando sobre os pares chave-valor
for chave, valor in meu_dict.items():
    print(f"{chave}: {valor}")
# Saída:
# a: 1
# b: 2
# c: 3

# Convertendo a visão iterável em uma lista de tuplas
items_list = list(meu_dict.items())
print(items_list)  # Saída: [('a', 1), ('b', 2), ('c', 3)]
```

O método `items()` é especialmente útil quando você precisa iterar sobre as chaves e valores de um dicionário ao mesmo tempo.

## Método keys()

* O método `keys()` em Python é usado para obter uma visão iterável de todas as chaves de um dicionário. A sintaxe é:

```python
dicionario.keys()
```

Aqui estão alguns exemplos de como utilizá-lo:

```python
# Exemplo básico de uso do keys()
meu_dict = {"nome": "Ana", "idade": 25, "cidade": "São Paulo"}

# Obtendo todas as chaves do dicionário
chaves = meu_dict.keys()
print(chaves)  # Saída: dict_keys(['nome', 'idade', 'cidade'])

# Convertendo a visão iterável em uma lista
lista_chaves = list(meu_dict.keys())
print(lista_chaves)  # Saída: ['nome', 'idade', 'cidade']
```

O método `keys()` é especialmente útil quando você precisa iterar sobre as chaves de um dicionário ou quando deseja verificar a existência de uma chave específica.

## Método pop()

* O método `pop()` em Python é usado para remover e retornar um elemento de uma lista ou dicionário. A sintaxe varia ligeiramente dependendo do tipo de objeto:

### Para Listas
O método `pop()` remove e retorna o elemento na posição especificada. Se nenhum índice for especificado, ele remove e retorna o último elemento da lista.

```python
# Exemplo básico de uso do pop() em listas
frutas = ['maçã', 'banana', 'cereja']

# Removendo o último elemento
ultima_fruta = frutas.pop()
print(ultima_fruta)  # Saída: cereja
print(frutas)  # Saída: ['maçã', 'banana']

# Removendo um elemento específico pelo índice
segunda_fruta = frutas.pop(1)
print(segunda_fruta)  # Saída: banana
print(frutas)  # Saída: ['maçã']
```

### Para Dicionários
O método `pop()` remove a chave especificada e retorna o valor correspondente. Se a chave não for encontrada, ele pode retornar um valor padrão se especificado.

```python
# Exemplo básico de uso do pop() em dicionários
meu_dict = {"nome": "Ana", "idade": 25, "cidade": "São Paulo"}

# Removendo uma chave específica
idade = meu_dict.pop("idade")
print(idade)  # Saída: 25
print(meu_dict)  # Saída: {'nome': 'Ana', 'cidade': 'São Paulo'}

# Removendo uma chave inexistente com valor padrão
pais = meu_dict.pop("pais", "Brasil")
print(pais)  # Saída: Brasil
print(meu_dict)  # Saída: {'nome': 'Ana', 'cidade': 'São Paulo'}
```

#### Outro exemplo:

```
contatos = {
  'alisson@gmail.com': {'nome': 'Alisson', 'telefone': '3333-0432'}
}
contatos.pop('alisson@gmail.com') # Saída: {'nome': 'Alisson', 'telefone': '3333-0432'}
contatos.pop('alisson@gmail.com', {}) # Saída: {}
```


O método `pop()` é muito útil para manipular listas e dicionários de forma dinâmica.

## Método popitem()

* O método `popitem()` em Python é usado para remover e retornar o último par chave-valor inserido em um dicionário.

#### A sintaxe é:

```python
dicionario.popitem()
```

#### Aqui estão alguns exemplos de como utilizá-lo:

```python
# Exemplo básico de uso do popitem()
meu_dict = {"nome": "Ana", "idade": 25, "cidade": "São Paulo"}

# Removendo o último par chave-valor inserido
ultimo_item = meu_dict.popitem()
print(ultimo_item)  # Saída: ('cidade', 'São Paulo')
print(meu_dict)  # Saída: {'nome': 'Ana', 'idade': 25}
```

#### Outro exemplo:

```
contatos = {
  'alisson@gmail.com': {'nome': 'Alisson', 'telefone': '3333-0432'}
}
contatos.popitem() # Saída: ('alisson@gmail.com', {'nome': 'Alisson', 'telefone': '3333-0432'})
contatos.popitem() # Saída: KeyError
```

### Detalhes Importantes⚠️
- **Versões do Python**: Em versões anteriores ao Python 3.7, o método `popitem()` removia um par chave-valor aleatório do dicionário.
- **Retorno**: O método retorna o par chave-valor removido como uma tupla.

## Método setdefault()

* O método `setdefault()` em Python é usado para obter o valor de uma chave específica em um dicionário. Se a chave não existir, ele a adiciona ao dicionário com um valor padrão e retorna esse valor.

#### A sintaxe é:

```python
dicionario.setdefault(chave, valor_padrao)
```

- **chave**: a chave que você deseja buscar no dicionário.
- **valor_padrao** (opcional): o valor a ser atribuído se a chave não existir. Se não for especificado, o valor padrão será `None`.

#### Aqui estão alguns exemplos de como utilizá-lo:

```python
# Exemplo básico de uso do setdefault()
meu_dict = {"nome": "Ana", "idade": 25}

# Obtendo o valor de uma chave existente
idade = meu_dict.setdefault("idade")
print(idade)  # Saída: 25

# Adicionando uma nova chave com valor padrão
cidade = meu_dict.setdefault("cidade", "São Paulo")
print(cidade)  # Saída: São Paulo
print(meu_dict)  # Saída: {'nome': 'Ana', 'idade': 25, 'cidade': 'São Paulo'}

# Usando setdefault() sem valor padrão
pais = meu_dict.setdefault("pais")
print(pais)  # Saída: None
print(meu_dict)  # Saída: {'nome': 'Ana', 'idade': 25, 'cidade': 'São Paulo', 'pais': None}
```

#### Outro exemplo:

```python
# Exemplo básico de uso do setdefault()
contatos = {'nome': 'Alisson', 'telefone': '3333-0432'}

contato.setdefault('nome', 'Fonseca') # 'Alisson'
contato # Saída: {'nome': 'Alisson', 'telefone': '3333-0432'}

contato.setdefault('idade', 30) # 30
contato # Saída: {'nome': 'Alisson', 'telefone': '3333-0432', 'idade': 30}
```

O método `setdefault()` é útil quando você deseja garantir que uma chave esteja presente no dicionário, com um valor padrão, se necessário.

## Método update()

* O método `update()` em Python é usado para atualizar um dicionário com os pares chave-valor de outro dicionário ou de um iterável de pares chave-valor.

#### A sintaxe é:

```python
dicionario.update(outro_dicionario)
```

#### Aqui estão alguns exemplos de como utilizá-lo:

### Atualizando com Outro Dicionário
```python
meu_dict = {"nome": "Ana", "idade": 25}
novo_dict = {"cidade": "São Paulo", "idade": 26}

meu_dict.update(novo_dict)
print(meu_dict)  # Saída: {'nome': 'Ana', 'idade': 26, 'cidade': 'São Paulo'}
```

### Atualizando com um Iterável de Pares Chave-Valor
```python
meu_dict = {"nome": "Ana", "idade": 25}
pares = [("cidade", "São Paulo"), ("idade", 26)]

meu_dict.update(pares)
print(meu_dict)  # Saída: {'nome': 'Ana', 'idade': 26, 'cidade': 'São Paulo'}
```

### Detalhes Importantes⚠️
- **Chaves Existentes**: Se a chave já existir no dicionário original, seu valor será atualizado com o valor do novo dicionário ou iterável.
- **Chaves Novas**: Se a chave não existir, ela será adicionada ao dicionário.

## Método values()

* O método `values()` em Python é usado para obter uma visão iterável de todos os valores de um dicionário.

#### A sintaxe é:

```python
dicionario.values()
```

#### Aqui estão alguns exemplos de como utilizá-lo:

```python
# Exemplo básico de uso do values()
meu_dict = {"nome": "Ana", "idade": 25, "cidade": "São Paulo"}

# Obtendo todos os valores do dicionário
valores = meu_dict.values()
print(valores)  # Saída: dict_values(['Ana', 25, 'São Paulo'])

# Convertendo a visão iterável em uma lista
lista_valores = list(meu_dict.values())
print(lista_valores)  # Saída: ['Ana', 25, 'São Paulo']
```

O método `values()` é especialmente útil quando você precisa iterar sobre os valores de um dicionário ou quando deseja acessar todos os valores de uma vez.

## Método in()

* O operador `in` em Python é usado para verificar se um elemento está presente em uma sequência, como uma lista, tupla, string ou dicionário. Ele retorna `True` se o elemento estiver presente e `False` caso contrário.

#### A sintaxe é:

```python
elemento in sequencia
```

#### Aqui estão alguns exemplos de como utilizá-lo:

### Em Listas
```python
frutas = ['maçã', 'banana', 'cereja']
print('maçã' in frutas)  # Saída: True
print('laranja' in frutas)  # Saída: False
```

### Em Strings
```python
texto = "Olá, mundo!"
print('Olá' in texto)  # Saída: True
print('oi' in texto)  # Saída: False
```

### Em Dicionários
Para dicionários, o operador `in` verifica a presença de uma chave:
```python
meu_dict = {"nome": "Ana", "idade": 25}
print('nome' in meu_dict)  # Saída: True
print('endereço' in meu_dict)  # Saída: False
```

O operador `in` é muito útil para realizar verificações rápidas e eficientes em várias estruturas de dados.

## Método del()

* O `del` em Python é uma instrução usada para deletar objetos. Pode ser usada para remover itens de listas, dicionários, ou até mesmo para deletar variáveis inteiras.

#### A sintaxe é:

```python
del objeto
```

### Exemplos de Uso

#### Remover um Item de uma Lista pelo Índice

```python
frutas = ['maçã', 'banana', 'cereja']
del frutas[1]
print(frutas)  # Saída: ['maçã', 'cereja']
```

#### Remover uma Fatia de uma Lista
```python
numeros = [0, 1, 2, 3, 4, 5]
del numeros[1:4]
print(numeros)  # Saída: [0, 4, 5]
```

#### Remover um Par Chave-Valor de um Dicionário
```python
meu_dict = {"nome": "Ana", "idade": 25, "cidade": "São Paulo"}
del meu_dict["idade"]
print(meu_dict)  # Saída: {'nome': 'Ana', 'cidade': 'São Paulo'}
```

#### Deletar uma Variável
```python
x = 10
del x
# print(x)  # Isso causará um erro porque x não existe mais
```

### Detalhes Importantes⚠️
- **Diferença entre `del` e Métodos como `pop()`**: Enquanto `del` é uma instrução que pode ser usada para deletar qualquer objeto, métodos como `pop()` são específicos para tipos de dados como listas e dicionários e retornam o valor removido.