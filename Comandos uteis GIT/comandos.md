**git --version -** [verifica a versão instalada]

**git status -** [mostra o estado dos arquivos e diretórios]

**git clone** `**link**` - clonar repositório existente

**git config --global user.name** `**"PrimeiroNome ÚltimoNome"**` [configura seu nome]

**git config --global user.email** `**"email@host.com"**` [configura seu e-mail]

**git init -** [inicia um repositório local]

**git commit `meuarquivo.txt`** [commit somente o arquivo especificado]

**git commit** `**arquivo1.txt arquivo2.txt`** [commit vários arquivos ao mesmo tempo]

**git commit** `**meuarquivo.txt**` **-m** `"mensagem de commit"` [commit informando uma mensagem]

**git commit --amend -m** `"nova mensagem de commit"` [altera a mensagem de commit realizada]

**git add .** [adiciona todos os arquivos ou diretórios modificados]

**git add** `**meuarquivo.txt**` [adiciona somente o arquivo especificado]

**git add** `**meudiretório**` [adiciona somente o diretório informado]

**git rm** `**meuarquivo.txt**` [remove somente o arquivo especificado]

**git rm -r `meudiretório`** [remove somente o diretório informado]

**git push origin main** [upload das alterações locais para o repositório online]

**git pull origin main** [download de todos os arquivos do repositório online]

**eval $(ssh-agent -s) -** inicializar o ssh agent 

**ssh-add** - Adicionar private key

**git clone `link do arquivo`** - clonar repositório

**ssh-keygen -t ed25519 -C `seu email`**

**openssl sha1 -** mostrar os 40 caracteres de encriptação