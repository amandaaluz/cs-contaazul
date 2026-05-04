# Conta Azul CS — Materiais de Treinamento

Site estático com os materiais pós-treinamento da Conta Azul Pro, hospedado na Vercel.

## Páginas

| URL | Arquivo |
|-----|---------|
| `/primeiros-passos` | `primeiros-passos.html` |
| `/faturamento-produtos` | `faturamento-produtos.html` |
| `/faturamento-servicos` | `faturamento-servicos.html` |
| `/nfce-frente-de-caixa` | `nfce-frente-de-caixa.html` |

## Estrutura

```
contaazul-cs/
├── faturamento-produtos.html
├── faturamento-servicos.html
├── nfce-frente-de-caixa.html
├── primeiros-passos.html
├── shared.css          ← design system compartilhado
├── vercel.json         ← configuração Vercel (cleanUrls, headers)
└── README.md
```

## Deploy na Vercel

### Opção 1 — Via GitHub (recomendado)
1. Crie um repositório no GitHub e envie esta pasta
2. Acesse [vercel.com](https://vercel.com) → **Add New Project**
3. Importe o repositório → clique em **Deploy**
4. A Vercel detecta o site estático automaticamente

### Opção 2 — Via Vercel CLI
```bash
npm i -g vercel
vercel
```

## Manutenção

- Para alterar o design (cores, fontes, layout): edite apenas `shared.css`
- Para alterar o conteúdo de uma página: edite o `.html` correspondente
- Qualquer push na branch `main` faz o redeploy automaticamente (via GitHub)
