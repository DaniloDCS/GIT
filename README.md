# 1. Instalando o GIT
    1.1. Link para Download: [baixar GIT](https://git-scm.com/download/win)
    1.2. Navegue até o diretório "Desktop" (Área de Trabalho).
        * Você poderá usar o Git Bash (comandos usados em Linux) 
        ou Git CMD (comandos usados no windows)
    1.3. Crie um diretório (uma pasta).
    1.4. Navege até o diretório criado.
    anteriormente e digite "git init" para iniciar um repositório.
        * CD nome_do_diretorio

# 2 Configurando o usuário
    2.1. git config --global user.email "you@example.com"
    2.2. git config --global user.name "Your Name"


# 3 Criando o arquivo README.md 
## 3.1 No Git Bash
    3.1.1. touch README.md
    3.1.2. ls para verificar os itens no diretório.

## 3.2 No Git CMD
    3.2.1. copy NUL README.md
    3.2.2. dir para verificar os itens no diretório.

# 4. Associando o repositório local ao remoto.
    4.1. git remote add origin https://github.com/seu_nome_de_usuario/desweb.git

# 5. Salvando os arquivos no diretório remoto (fazer um commit).
    5.1. git add nome_do_aquivo - (Arquivo específico)
    5.2. git add . - (Todos os arquivos)
    5.3. git satus (visualizar o status)
    5.4. git commit -m "texto aqui" (Descerver o commit)
    5.5. git push origin master (Salvar arquivis no diretório remoto)

# 6. COMANDOS BÁSICOS
    6.1. mkdir name_folder - Criar diretório.
    6.2. clear - Limpar o GUI (Interface Gráfica do Usuário)
    6.3. ls - listar o itens que tem no diretório atual.
    6.4. touch <name_file>.<extensão> criar arquivo.
    6.5. git init para iniciar um diretório.
    6.6. Git pull é pra resolver conflitos.