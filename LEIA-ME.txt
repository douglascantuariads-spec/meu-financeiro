# Meu Financeiro — versão inicial 0.1

## O que já funciona
- Cadastro de despesas com local, descrição, valor, data, categoria e forma de pagamento.
- Cadastro de receitas com descrição, valor, data e categoria.
- Saldo automático por mês (receitas menos despesas).
- Filtro por mês.
- Gráficos simples de despesas por categoria e forma de pagamento.
- Exclusão de lançamentos.
- Exportação e importação de backup JSON.
- Relatório preparado para impressão/salvar em PDF.
- Estrutura PWA para instalação na tela inicial e cache offline após primeiro acesso.

## Testar no Windows
Abra `index.html` no Edge ou Chrome. Os dados ficam no armazenamento local desse navegador.

## Publicar para instalar no iPhone
Para instalação como PWA, os arquivos precisam estar hospedados em HTTPS. Uma opção simples é publicar esta pasta em GitHub Pages. Depois, no iPhone:
1. Abra o endereço publicado no Safari.
2. Toque em Compartilhar.
3. Escolha "Adicionar à Tela de Início".
4. Abra o ícone Meu Financeiro.

## Privacidade e backup
Os dados ficam no armazenamento local do navegador/aplicativo e não são enviados a um servidor pelo código desta versão. Exportar backup JSON regularmente. Não limpar os dados do Safari/navegador sem exportar antes.

## Limitações desta versão
- Ainda não há edição de lançamentos (somente exclusão e novo cadastro).
- Compras parceladas e faturas de cartão ainda não foram implementadas.
- O PDF usa a função de impressão do navegador; escolha "Salvar como PDF".
- A instalação PWA depende de hospedagem HTTPS. Abrir o HTML diretamente no iPhone não instala o app.
