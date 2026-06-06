# Paginas legais publicas

Publique estes arquivos no dominio oficial antes de enviar o app para a Google Play:

- `politica-de-privacidade/index.html` em `/politica-de-privacidade`
- `termos-de-uso/index.html` em `/termos-de-uso`
- `excluir-conta/index.html` em `/excluir-conta`

Dados configurados:

- Email de suporte: `bruno.tar.gz@gmail.com`
- Controlador/responsavel: `Bruno Vieira`
- Dominio: `eartraininglab.com.br`

Antes da publicacao comercial, revise os textos com apoio juridico.

As URLs precisam ser configuradas nos ambientes EAS:

```env
EXPO_PUBLIC_LEGAL_BASE_URL=https://eartraininglab.com.br
EXPO_PUBLIC_PRIVACY_POLICY_URL=https://eartraininglab.com.br/politica-de-privacidade
EXPO_PUBLIC_TERMS_URL=https://eartraininglab.com.br/termos-de-uso
EXPO_PUBLIC_ACCOUNT_DELETION_URL=https://eartraininglab.com.br/excluir-conta
```
