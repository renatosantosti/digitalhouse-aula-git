# digitalhouse-aula-git

Usando git com a turma da DH em 03/2022.

# Roteiro dessa aula: ( usando MarkDown)

## 1 - Criar um repositório e conectar : ok

### 1.1 git init ou git clone

### 1.2 git add remote add origin <url.git>

### 1.3 git pull origin main our git pull <url.git> main

### 1.4 git remote set-url origin <url.git> main

## 2 - Alterar algum arquivo e enviar para o repositório ok

### 2.1 git add .

### 2.2 git commit -m "modificando alguma coisa"

### 2.3 git push

## 3 - Criar uma nova branch (ramificar o repositório)

### 3.1 - criar uma nova branch : usar o comando: git branch <nome_da_branch> ou git checkout -b <nome_da_branch>

#### 3.1.1 fazer checkout : como -> git checkout <nome_da_branch>

#### 3.1.2 baixar o que estiver na main --> git pull origin main

### 3.2 - criar um novo arquivo e alterar ele

          git add .

### 3.3 - subir as alterações da branch para o repositório na mesma branch(remote)

          git commit -m "texto explicativo"
          git push
