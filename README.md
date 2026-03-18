# Osasco Express App 🛵

Sistema de gestão logística — Dashboard Fratelli, Proposta Comercial e Orçamento IA.

## Arquivos

```
/
├── index.html        ← App shell (navegação entre telas)
├── dashboard.html    ← Dashboard Fratelli Jan-Fev/2026
├── proposta.html     ← Proposta comercial mobile
├── orcamento.html    ← Orçamento inteligente com IA
├── manifest.json     ← PWA config
├── sw.js             ← Cache offline
├── netlify.toml      ← Deploy automático Netlify
└── _redirects        ← Rotas Netlify
```

## Deploy automático GitHub → Netlify

1. Suba este repositório no GitHub
2. No Netlify: **Add new site → Import from Git → GitHub**
3. Selecione este repositório
4. Build command: deixe **vazio**
5. Publish directory: **.**  (ponto)
6. Clique **Deploy site**

A partir daí, todo `git push` atualiza o site automaticamente.

## Instalar como app no celular

Após o deploy, abra o link no celular:
- **iPhone (Safari):** Compartilhar → Adicionar à Tela de Início
- **Android (Chrome):** Menu ⋮ → Adicionar à tela inicial

## Ícones (necessário para PWA)

Gere os ícones em: https://www.appicon.co
- `icon-192.png` (192×192 px)
- `icon-512.png` (512×512 px)

## Contato

- contato@osascoexpress.com.br
- (11) 98666-1784
- Av. Diogo Antônio Feijó, 855 – KM18, Osasco/SP
