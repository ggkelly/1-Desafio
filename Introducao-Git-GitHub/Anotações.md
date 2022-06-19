# INTRODUÇÃO AO GIT E AO GITHUB

### Entendendo o que é o Git e sua importância

- Link para download do Git: https://git-scm.com/downloads
- Git é um software para desenvolvermos algoritmos ao mesmo tempo em que temos acesso a todas as versões.
- GitHub - Onde guardar os arquivos (repositório remoto, servidor)
- Vantagens:
  - Controle de versão
  - Armazenamento em nuvem
  - Trabalho em equipe
  - Melhorar seu código
  - Reconhecimento

### Navegação básica no terminal e instalação

git - linha de comando

Windows:

- cd - navegar nas pastas
- cd .. - voltar uma pasta
- cd e primeiras letras do arquivo mais tab - completa o nome do arquivo
- dir ou ls - listar os diretórios dentro da pasta em que estamos
- mkdir - criar pasta
- del - deletar o que tem dentro da pasta
- rmdir - deletar a pasta com tudo
- cls ou Ctrl L - limpar o terminal
- echo - printa uma frase na tela
- 

### Entendendo como o Git funciona por baixo dos panos

- SHA1(Secure Hash Algorithm) - é um conjunto de funções hash criptográficas projetadas pela NSA (Agência de Segurança Nacional dos EUA).
- A encriptação gera um conjunto de caracteres identificadores de 40 dígitos. 
- Permite identificar os arquivos de forma rápida e segura.

### Objetos do Git

- Blobs - Bloco base de composição.
- Tree - Monta toda a estrutura de onde estão os arquivos.
- Commit - Objeto que junta tudo e dá sentido à mudança que foi feita.

### Chaves SSH e Tokens

- Chave SSH: Forma de estabelecer uma conexão segura entre a conta no GitHub e a máquina.
- Tokens: Se assemelha mais ao estilo nome e senha.

### Iniciando o Git e criando um commit

Arquivo Markdown: Forma mais humana de se escrever um arquivo HTML sem precisar entender como ele funciona.

HTML: Estrutura base de qualquer site na internet.

- Iniciar o Git:
  - git init
    - Inicia o git - cria uma pasta .git
    - Inicializa o repositório
- Iniciar o versionamento
  - git add ou git add * ou git add . - move os arquivos e dá início ao versionamento (move os arquivos para a fase staged)
- Criar um commit
  - git commit 

### Ciclo de vida dos arquivos dentro do Git

- Untracked: arquivos que o git não tem ciência deles.

- Tracked: Arquivos que o got tem ciência que existem:
  - Modified - arquivos que já foram modificados
  - Unmodified - arquivos que nunca foram modificados
  - Staged - onde ficam os arquivos que estão se preparando para fazer parte de outro tipo de agrupamento

Repositório local - só commit

- Empurra (push) daqui para o GitHub (repositório remoto)

#### Funções do Git

- git init - criar pasta .git

- git status - Vai dizer o estágio do ciclo de vida que o arquivo se encontra

- mv - mover arquivos

- git add * , git add . - pega tudo que foi modificado no diretório de trabalho e adiciona ao staged

- git add nomeDoArquivo - adiciona o arquivo selecionado ao staged

- git commit -m "Deixar uma mensagem falando sobre o que é o arquivo" - move o arquivo para o repositório local

- git push origin main - envia cópia do arquivo para o repositório online.

- git clone link URL do arquivo no GitHub - passa cópia do arquivo para a máquina

- git pull origin main - puxa a versão do arquivo que está no GitHub para o Git

- git remote -v - mostra a URL para onde o repositório está direcionado

  





