# Relatório de QA - https://achados-app.pages.dev

| Teste | Resultado | Detalhe |
|---|---|---|
| Listagem pública responde 200 | PASSOU | status 200 |
| /api/me sem login retorna 401 | PASSOU | status 401 |
| Criar item sem login retorna 401 | PASSOU | status 401 |
| Encerrar caso sem login retorna 401 | PASSOU | status 401 |
| Filtro com categoria inválida retorna 400 | PASSOU | status 400 |
| Categoria inválida rejeitada (400) | PASSOU | status 400 |
| Data futura rejeitada (400) | PASSOU | status 400 |
| Descrição curta rejeitada (400) | PASSOU | status 400 |
| Título com <script> é gravado como texto (201) | PASSOU | status 201 |
| Título volta literal (sem execução; a UI usa textContent) | PASSOU |  |
| Reivindicar o próprio item retorna 403 | PASSOU | status 403 |
| Filtros combinados retornam só perdi/garrafas | PASSOU |  |

**Total: 12/12 passaram.**
