# Privacy Policy — OmniPlay Mobile

Política de privacidade pública do app móvel, exigida pela App Store da Apple
(item App Privacy + URL de Política de Privacidade) e pela LGPD.

## Arquivos

| Arquivo | Descrição |
|---|---|
| `index.html` | HTML bilíngue (PT-BR + EN) auto-contido, pronto pra hostar em qualquer URL pública. CSS + JS inline, sem dependência externa. |
| `privacy-policy-pt-BR.md` | Versão Markdown PT-BR, fonte editorial. |
| `privacy-policy-en.md` | Versão Markdown EN, fonte editorial. |

## Como hostar

### Opção 1 — Subdomínio dedicado (recomendado)

Hospeda o `index.html` em `https://omniplay.com.br/privacidade` ou
`https://privacy.omniplay.com.br`. Qualquer hosting estático serve:

- **Vercel:** drag & drop do arquivo no dashboard
- **Netlify:** idem
- **GitHub Pages:** push num repo público + ativa Pages
- **S3/CloudFront:** upload + bucket público
- **Apache/Nginx:** cópia no docroot

URL final fica em formato `https://<host>/` (o `index.html` é servido por default).

### Opção 2 — Rota no site principal

Se já existe um site Next.js/React em `omniplay.com.br`, salva como rota estática
em `public/privacidade.html` ou cria componente que renderiza o conteúdo do markdown.

## URL pública pra App Store Connect

Depois de hospedar, cadastre a URL em:

1. **App Store Connect → My Apps → OmniPlay → App Privacy** → Privacy Policy URL
2. **App Information** → Privacy Policy URL (mesma URL)

A URL precisa retornar **200 OK** sem login. Apple testa antes de aprovar.

## Antes de subir, REVISAR

Marcadores que precisam ser preenchidos:

- `CNPJ XX.XXX.XXX/0001-XX` — CNPJ exato da Netplay
- `[cidade/UF]` (só no markdown) — endereço sede
- `dpo@netplay.net.br` — confirmar se esse endereço existe e quem responde
- `[Nome do DPO]` (só no markdown) — nome do encarregado de proteção de dados
- `[Endereço da Netplay]` (só no markdown) — endereço completo
- `omniplay.com.br/privacidade` e `omniplay.com.br/privacy` — confirmar URLs finais
- `privacidade@netplay.net.br` / `suporte@netplay.net.br` — confirmar caixas ativas

## Versionamento

Quando atualizar a política:

1. Edita `index.html` E os dois `.md` (manter sincronizados)
2. Atualiza **"Última atualização"** / **"Last updated"** no topo
3. Incrementa **"Versão"** / **"Version"** (semver: 1.0 → 1.1 patch, 1.0 → 2.0 mudança significativa)
4. Avisa usuários por email + push pra mudanças significativas (conforme Seção 13)

## Notas legais

- Documento elaborado em conformidade com a **Lei nº 13.709/2018 (LGPD)** brasileira.
- Versão EN incorpora princípios do **GDPR** para usuários internacionais.
- **Não substitui assessoria jurídica.** Antes do release público recomendamos revisão por advogado(a) especializado(a) em direito digital / LGPD.
