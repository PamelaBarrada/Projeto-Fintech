# MinhaCarteira — Painel Financeiro (Fintech)

Tela única do projeto Fintech **MinhaCarteira**, desenvolvida com **HTML5**, **CSS3** e **Tailwind CSS**.

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

