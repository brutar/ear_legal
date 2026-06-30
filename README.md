# Ear Training Lab - Paginas legais

Repositorio estatico com as paginas legais publicas do aplicativo.

- `politica-de-privacidade/index.html` em `/politica-de-privacidade`
- `termos-de-uso/index.html` em `/termos-de-uso`
- `excluir-conta/index.html` em `/excluir-conta`
- `confirmar-email/index.html` em `/confirmar-email`

## Publicacao

Projeto preparado para deploy como site estatico na Vercel.

Rotas esperadas no dominio final:

- `https://www.eartraininglab.com.br/politica-de-privacidade`
- `https://www.eartraininglab.com.br/termos-de-uso`
- `https://www.eartraininglab.com.br/excluir-conta`
- `https://www.eartraininglab.com.br/confirmar-email`

Configuracao esperada:

1. Projeto Vercel conectado ao repositorio `brutar/ear_legal`.
2. Framework preset: `Other`.
3. Build command vazio.
4. Output directory vazio ou raiz do repositorio.
5. Dominios `eartraininglab.com.br` e `www.eartraininglab.com.br` adicionados ao projeto Vercel.
6. DNS no Registro.br apontando para os registros indicados pela Vercel.

## Revisao

Antes da publicacao comercial, revise os textos com apoio juridico.

## Supabase Auth

Use `https://www.eartraininglab.com.br/confirmar-email` como redirect de confirmacao de cadastro no Supabase Auth.
