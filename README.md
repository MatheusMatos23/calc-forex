# Forex Split · 利润分配

Calculadora de divisão de lucros de operações Forex. Funciona no celular e no desktop e pode ser instalada como app (PWA).

- Informe o capital operado e o lucro; escolha a moeda (US$, R$, ¥, USDT).
- Regra padrão: Trader (chinês) 60% · Investidor 20% · Sócios 20% divididos igualmente entre 3.
- As porcentagens e as pessoas podem ser editadas na aba **Divisão** (ficam salvas no aparelho).
- Cotação opcional para ver cada parte também em R$.
- Botão para copiar o resumo (para WhatsApp) e histórico local.

Publicado via GitHub Pages (branch `main`, pasta raiz).
- **Painel**: importa o PDF do relatório do MetaTrader 5 (lido no próprio navegador), mostra indicadores, evolução do saldo e o lucro entre importações, e envia o lucro da semana direto para a divisão. Backup/restauração em JSON.
- **Painel compartilhado (somente leitura)**: o administrador publica os dados criptografados em `data/painel.json` via API do GitHub (token fine-grained só deste repositório). Quem recebe o link `#v=<chave>` vê apenas o Painel, que se atualiza sozinho.
