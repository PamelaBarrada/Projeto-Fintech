# MinhaCarteira — Painel Financeiro (Fintech)

Tela única do projeto Fintech **MinhaCarteira**, desenvolvida com **HTML5**, **CSS3** e **Tailwind CSS**, como parte do desafio de Front-end.

## 🖥️ Sobre a tela

A tela representa o **Painel Financeiro (Início)** do app, reunindo em um só lugar:

- Visão geral do saldo total, limite disponível e investimentos;
- Card da conta principal com saldo disponível;
- Ações rápidas (Enviar, Receber, Transferir, PIX);
- Resumo de receitas e despesas do mês;
- Gastos por categoria.

## 🧱 Tecnologias utilizadas

- **HTML5** — estrutura da página (`index.html`)
- **CSS3** — estilos próprios, em arquivo separado (`css/styles.css`)
- **Tailwind CSS** — compilado localmente (sem depender de CDN/internet), usado para todo o layout, grid e responsividade

> Não há uso de JavaScript neste projeto — não é necessário para esta atividade.

## 📁 Estrutura de pastas

```
MinhaCarteira/
├── index.html        # Tela única (Painel Financeiro)
├── css/
│   └── styles.css     # Tailwind CSS compilado + estilos próprios do projeto
└── images/
    └── bg-city.jpg     # Imagem de fundo
```

## 📱 Responsividade

O layout foi construído mobile-first com os breakpoints do Tailwind CSS (`sm:`), adaptando grids de 3/4 colunas no desktop para 1/2 colunas em telas de celular.

## ▶️ Como visualizar

Basta abrir o arquivo `index.html` diretamente no navegador (duplo clique). Não é necessário servidor, instalação ou internet — todo o CSS já está compilado localmente no projeto.

## 🚀 Como publicar no GitHub

```bash
# 1. Entrar na pasta do projeto
cd MinhaCarteira

# 2. Iniciar o repositório Git
git init

# 3. Adicionar todos os arquivos
git add .

# 4. Criar o primeiro commit
git commit -m "Tela do painel financeiro - projeto Fintech"

# 5. Renomear a branch principal (se necessário)
git branch -M main

# 6. Conectar ao repositório remoto (crie antes um repositório PÚBLICO no GitHub)
git remote add origin https://github.com/SEU-USUARIO/MinhaCarteira.git

# 7. Enviar os arquivos para o GitHub
git push -u origin main
```

Depois de subir, confirme que o repositório está marcado como **Público** em *Settings > General* no GitHub, e copie o link do repositório para colar no PDF de entrega.
