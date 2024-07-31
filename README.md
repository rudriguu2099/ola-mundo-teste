Claro! Aqui está a documentação formatada em Markdown:

---

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

## O que vamos fazer?
Mostrar o passo a passo para configurar a chave SSH do computador do laboratório na conta do GitHub. (15 min)

## Passo a Passo

### Gerar e Configurar Chave SSH
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

4. Colar a chave SSH na conta do GitHub:
   - Acessar Configurações -> SSH & GPG keys -> New SSH key
   - Colar a chave e salvar como `ufc`

### Criar e Clonar Repositório no GitHub
1. Criar um repositório virtual no GitHub.
2. Clonar o repositório vazio na área de trabalho:
   ```bash
   git clone <url do repositório>
   ```

### Adicionar e Comitar Arquivo README.md
1. Adicionar um arquivo `README.md` no repositório clonado.
2. Adicionar todos os arquivos para commit:
   ```bash
   git add .
   ```
3. Fazer o commit:
   ```bash
   git commit -m "primeiro commit"
   ```

### Configurar URL do Repositório Remoto e Enviar Commit
1. Configurar a URL do repositório remoto:
   ```bash
   git remote set-url origin "git@github.com/<user>/<repositorio>.git"
   ```
   - Alternativamente, mostrar no próprio PC como copiar a URL pelo GitHub Web.
2. Enviar o commit:
   ```bash
   git push
   ```

(30 min mínimo)

## Fim do Trabalho

---

Espero que isso ajude! Se precisar de mais ajustes ou informações adicionais, estou à disposição.
