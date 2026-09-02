# Site institucional — SimplificAI

Landing page estática da SimplificAI: automação de dados e processos para PMEs.

**Slogan:** Simplificando sob medida a gestão e organização da sua empresa.

## Estrutura

```
index.html          página única (HTML + CSS + JS inline, sem framework)
assets/             prints anonimizados (webp), logo, favicons e imagem de compartilhamento
robots.txt
sitemap.xml
```

## Stack

Nenhuma. HTML, CSS e JavaScript puros num único arquivo, sem build e sem dependências.
Tipografia via Google Fonts (Archivo, Inter, JetBrains Mono).

## Publicação

Hospedado na Vercel, com deploy automático a cada push na branch `main`.

## Confidencialidade

Todos os prints de sistemas em `assets/` são anonimizados: nomes de clientes,
fornecedores, colaboradores, cidades e valores reais foram ocultados ou
substituídos por dados fictícios plausíveis. Nenhum cliente é identificado.
Não subir para este repositório nenhum arquivo com dado real de cliente.

## Pendências

- [ ] Registrar domínio próprio e apontar para a Vercel
- [ ] Atualizar `canonical`, Open Graph, `robots.txt` e `sitemap.xml` com o domínio definitivo
- [ ] Trocar dois ou três cases industriais por casos de comércio ou serviço
- [ ] Verificar no Google Search Console


## Estrutura de arquivos

Todos os arquivos ficam na raiz do repositorio: index.html, os prints em .webp,
logo, favicons, og-image.jpg, robots.txt e sitemap.xml.
