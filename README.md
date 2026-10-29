# ClientFlow

Projeto demonstrativo independente com **identidade visual própria**, interface responsiva, API REST em Node.js e persistência em JSON.

## Executar

Requer Node.js 20+.

```bash
npm test
npm start
```

Acesse http://localhost:3000. Para outra porta: `PORT=4000 npm start` (PowerShell: `$env:PORT=4000; npm start`).

## Recursos

- Criar, consultar, editar e excluir registros.
- Pesquisa, filtros, indicadores e exportação CSV.
- Modais acessíveis, navegação por teclado, redução de movimento e adaptação a diferentes larguras de tela.
- API: `GET /api/health`, `GET/POST /api/records`, `PUT/DELETE /api/records/:id`.
- Dados iniciais **fictícios**, armazenados em `data/records.json`.
- Sem dependências npm externas; o Google Fonts é opcional e exige conexão.

## Limitações

Projeto educacional, sem login, multiusuário, banco relacional ou integração com pagamentos reais. Não é adequado para produção sem autenticação, autorização, auditoria, rate limiting e armazenamento apropriado.
