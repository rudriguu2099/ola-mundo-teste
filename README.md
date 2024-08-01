# Documentação Equipe 4: Gerência de Configuração

## Integrantes e Funções
- Emily Wictoria
- João Gabriel
- Rodrigo Rodrigues
- Cauan Ricardo
- Guilherme Cardoso
- Maria Beatriz
- Kaylanne De Jesus
- Ana Letícia
- Pedro Altino

(Funções a definir: Apresentadores, Monitores, Produtores de Material p/ Apresentação)

## Pré-requisitos
- Laboratório disponível
- Todos (ou a maioria) com uma conta no GitHub para agilizar a dinâmica
- Se a pessoa for fazer no seu notebook, precisará do Git já instalado (também para agilizar a dinâmica)
  
## Material Necessário:
- Dontpad com os comandos e esse manual de instruções
- (talvez slides + visuais para elucidar a explicação)
- O download de um `README.md` previamente pronto para a pessoa baixar no pc e diretamente adicionar ao repositório (agilizar)

## Passo a Passo

### Passo 1: Gerar e Configurar Chave SSH
1. Abra o terminal.
2. Gerar a chave SSH:
   ```bash
   ssh-keygen
   ```
3. Navegar para o diretório `.ssh`:
   ```bash
   cd
   cd .ssh
   explorer.exe .
   ```
4. Abrir o arquivo `id_rsa.pub` com o Bloco de Notas e copiar a chave SSH.

### Passo 2: Configurar SSH no GitHub e Criar Repositório
1. Colar a chave SSH na conta do GitHub:
   - Acesse Settings -> SSH & GPG keys -> New SSH key
   - Cole a chave e salve como `PC ufc`
2. Criar um repositório virtual no GitHub:
   - Fazer login na sua conta do GitHub.
   - Clicar no botão "New" ou "Novo repositório" na página inicial.
   - Preencher o nome do repositório e a descrição (opcional).
   - Escolher se o repositório será público ou privado.
   - Clicar em "Create repository" para finalizar a criação.

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
5. Navegar para o diretório do repositório clonado:
   ```bash
   cd <nome do repositório>
   ```
6. Adicionar um arquivo `README.md` no repositório clonado.
7. Adicionar todos os arquivos para commit:
   ```bash
   git add .
   ```
8. Configurar a URL do repositório remoto:
   ```bash
   git remote set-url origin "git@github.com:<seunomenogithub>/<repositorioqvccriou>.git"
   ```
9. Fazer o commit:
   ```bash
   git commit -m "primeiro commit"
   ```
   - Alternativamente, mostrar no próprio PC como copiar a URL pelo GitHub Web.
10. Enviar o commit:
    ```bash
    git push -u origin master
    ```

### Estimativas de Tempo:
- Chave SSH: 12-15 minutos
- Criação de repositório no GitHub: 5 minutos
- Configurar Git: 8-10 minutos
- Commit: 20-30 minutos

## Fim do Trabalho
