# STAK Digital

Landing page da **STAK Digital**, especialista em SEO local e Google Meu Negócio.

Projeto estático de página única, sem build tools, sem dependências além de CDNs.

## Como visualizar

Não é necessário servidor — basta abrir o arquivo diretamente no navegador:

```bash
# macOS
open index.html

# Linux
xdg-open index.html
```

## Stack

- HTML, CSS e JavaScript puros — tudo em `index.html`
- Google Fonts e Font Awesome via CDN (únicas dependências externas)
- Sem frameworks, sem bundler

## Estrutura

```
index.html   # página completa (estrutura, estilos e scripts)
images/      # logos e ícones da marca
```

## Identidade visual

| Cor | Valor |
|---|---|
| Azul principal | `#185FA5` |
| Verde crescimento | `#1D9E75` |
| Grafite neutro | `#2C2C2A` |
| Azul claro (fundo) | `#E6F1FB` |
| Verde WhatsApp | `#25D366` |

Tipografia: Google Fonts, estilo moderno/profissional.

## Desenvolvimento

Sem etapa de build, sem testes automatizados, sem gerenciador de pacotes. Edite `index.html` diretamente.

Mais detalhes de convenções e seções da página em [`CLAUDE.md`](./CLAUDE.md).
