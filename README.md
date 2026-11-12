# Perdido? Achado!

Plataforma web de **achados e perdidos para empresas**. Shoppings, universidades, academias, hotéis e outras organizações cadastram os itens encontrados, controlam prazos e registram as retiradas. Quem perdeu um objeto busca **sem precisar de cadastro**.

## Como funciona

- **Empresa (cliente pagante):** faz login, cadastra os itens achados (título, categoria, foto, data e hora de entrada), acompanha o armário e registra a retirada quando o dono aparece. Contrata o serviço por **assinatura mensal**.
- **Quem perdeu (usuário público):** descreve o que perdeu e onde, e recebe as possíveis correspondências e a empresa responsável. A retirada é feita **presencialmente** na empresa.
- **Privacidade:** o catálogo completo de itens nunca fica público. A pessoa só vê o que combina com a descrição que informou.

## Páginas

| Arquivo               | Descrição                                                                                               |
| --------------------- | ------------------------------------------------------------------------------------------------------- |
| `index.html`          | Landing page: recursos, comparativo, planos, depoimentos e modal "Perdi um objeto".                     |
| `painel-armario.html` | Painel da empresa: 20 itens fictícios com filtro por texto, categoria e data, e modal "Cadastrar item". |
| `historico.html`      | Histórico de entradas e retiradas, com funcionário responsável e nome de quem recebeu o item.           |

Fluxo de navegação: a landing page leva ao painel (botões "Entrar", "Começar agora", "Assinar…" e outros). O logo do painel volta para a landing page, e as abas **Armário** e **Histórico** ligam as duas páginas internas.

## Como abrir

Não precisa instalar nada. Abra o `index.html` no navegador.
