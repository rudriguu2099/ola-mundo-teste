# Documentação Equipe 4: Gerência de Configuração

## Integrantes
- Emily
- João
- Rodrigo
- Cauan
- Gui
- Bee
- Kaylanne
- Ana
- Pedro

## Pré-requisitos
- Laboratório disponível
- Todos (ou a maioria) com uma conta no GitHub
- Se a pessoa for fazer no seu notebook, precisará do Git instalado

## Passo a Passo

### Passo 1: Gerar e Configurar Chave SSH
1. Gerar a chave SSH:
   ```bash
   ssh-keygen
   ```
2. Navegar para o diretório `.ssh`:
   ```bash
   cd
   cd .ssh
   explorer.exe .
   ```
3. Abrir o arquivo `id_rsa.pub` com o Bloco de Notas e copiar a chave SSH.

### Passo 2: Configurar SSH no GitHub e Criar Repositório
1. Colar a chave SSH na conta do GitHub:
   - Acessar Configurações -> SSH & GPG keys -> New SSH key
   - Colar a chave e salvar como `ufc`
2. Criar um repositório virtual no GitHub.

### Passo 3: Configurar Git e Realizar o Primeiro Commit
1. Abrir o Git Bash.
2. Inicializar o repositório local:
   ```bash
   git init
   ```
3. Configurar o nome de usuário e o email:
   ```bash
   git config user.name "Seu Nome"
   git config user.email "seu.email@example.com"
   ```
4. Clonar o repositório vazio na área de trabalho:
   ```bash
   git clone <url do repositório>
   ```
5. Adicionar um arquivo `README.md` no repositório clonado.
6. Adicionar todos os arquivos para commit:
   ```bash
   git add .
   ```
7. Configurar a URL do repositório remoto:
   ```bash
   git remote set-url origin "git@github.com:<seunomenogithub>/<repositorioqvccriou>.git"
   ```
8. Fazer o commit:
   ```bash
   git commit -m "primeiro commit"
   ```
   - Alternativamente, mostrar no próprio PC como copiar a URL pelo GitHub Web.
9. Enviar o commit:
   ```bash
   git push
   ```

## Fim do Trabalho
