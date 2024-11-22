# README

## Descrição do Repositório
Este repositório foi criado como parte de um exercício no **4º período**, com o objetivo de revisar conceitos do Git. O projeto envolve o gerenciamento de versões de arquivos HTML e imagens, simulando um fluxo básico de desenvolvimento.

## Passos Realizados

### 1. Clonando o Repositório
Foi clonado um repositório vazio usando o comando:
```bash
git clone https://github.com/thiagocds01/Revis-o-N2.git
```

### 2. Verificando o Conteúdo
Após clonar, foi confirmado que o repositório estava vazio:
```bash
ls
```

### 3. Adicionando o Primeiro Arquivo
Um arquivo inicial chamado `index.index` foi criado e adicionado ao repositório:
```bash
git add .
git commit -m "criação de index da pagina"
```
O commit foi enviado ao repositório remoto:
```bash
git push origin main
```

### 4. Modificação do Projeto
O arquivo `index.index` foi removido, e novos arquivos foram adicionados:
- **`imagem/gato.jpg`**: uma imagem do gato.
- **`index.html`**: uma nova página HTML.

Estes arquivos foram adicionados e um novo commit foi realizado:
```bash
git add .
git commit -m "inserindo foto do gato"
```

As alterações foram enviadas ao repositório remoto:
```bash
git push origin main
```

## Estrutura do Repositório
Após as mudanças, o repositório possui a seguinte estrutura:
```
Revis-o-N2/
│
├── imagem/
│   └── gato.jpg
│
└── index.html
```

## Comandos Úteis
- **Status do Repositório:**
  ```bash
  git status
  ```
- **Adicionar Arquivos:**
  ```bash
  git add .
  ```
- **Realizar Commit:**
  ```bash
  git commit -m "mensagem do commit"
  ```
- **Enviar Alterações:**
  ```bash
  git push origin main
  ```