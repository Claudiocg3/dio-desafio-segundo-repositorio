### ***Benefícios do Git/Github***

- Controle de versão
- Armazenamento em nuvem
- Trabalho em equipe
- Melhora seu código
- Reconhecimento

### ***Como o Git funciona***

- ***SHA1***

  *SHA Significa **Secure Hash Algoritm (Algorítimo de Hash Seguro)** e é um conjunto de funções hash criptográficas. A encriptação gera um conteúdo de caracteres de 40 dígitos. O SHA1 é um alagarítimo de encriptação e serve de identifcação. É uma forma curta de representar um arquivo.*

- ***Objetos fundamentais***

  | *Objetos* | *Descrição* | *Exemplos*|
  | :---:| :---: | :---: |
  | ***Blobs*** | *Contém metadados* | *ex: tipo de objeto, tamanho do arquivo e string* |
  | ***Trees*** | *Armazena Blobs* | *ex: contém metadados, nome do arquivo e estrutura do arquivo* |
  | ***Commits*** |  *refere-se ao processo de tornar permanente um conjunto de alterações | efetiva as alterações.*| 

- ***Sistema distribuído seguro***

  |*Comando* | *Exemplos* |
  | :---: | :---: |
  | *Chave SSH e Tokens* | *ex: ssh-keygen -t ed25519 -C  e-mail* |

- ***Comados básicos***

  |*Comando* | *Exemplo* |
  | :---: | :---: |
  | ***git init*** | *é um comando único que se usa durante a configuração inicial de um novo repositório* |
  | ***git add*** | *adiciona uma alteração no diretório ativo à área de staging. Ele diz ao Git que você quer incluir atualizações a um arquivo específico no próximo commit. ex: git add * que adiciona tudo ou  git add + arquivo* |
  |***git commit*** | *criar commit. ex: git commit -M*| 
  | ***git status*** | *exibe as condições do diretório de trabalho e da área de staging.*|
  | ***ls***| *revela arquivos*
  | ***ls - a*** | *revela arquivos ocultos*
  | ***mv*** | *move arquivos* |
  | ***rm***| *remove arquivos* |

- ***Configurando o primeiro repositório***

  | *Comados* |
  | :---:|
  *git config --global user.e-mail + "e-mail"*
  *git config --global user.name + "nome usuário"*
  *git config --list :"listar configuração"*
  *git config --global --unset : "remove configuração" ex: user.name*

- ***Criando primeiro repositório***

  | *Comando* | *Exemplo* |
  | :---: | :---: |
  | ***git remote add origin*** | *link copiado do github*
  | ***git remote -v*** | *lista reositórios remotos que já está cadastrado* |
  | ***git push origin*** | *empurra para o link repositório no Github* |

