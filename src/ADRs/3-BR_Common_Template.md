---
#Configuração do template Jekyll "Just the Docs"
pai: Decisões
pedido_nav: 100
título: Modelo ADR

# Estes são elementos opcionais. Sinta-se à vontade para remover qualquer um deles.
# status: {proposto | rejeitado | aceito | obsoleto | … | substituído por [ADR-0005](0005-example.md)}
# data: {AAAA-MM-DD quando a decisão foi atualizada pela última vez}
# decisores: {liste todos os envolvidos na decisão}
# consultado: {liste todas as pessoas cujas opiniões são solicitadas (normalmente especialistas no assunto); e com quem existe uma comunicação bidirecional}
# informado: {liste todos que são mantidos atualizados sobre o progresso; e com quem existe uma comunicação unilateral}
---
<!-- precisamos desabilitar o MD025, pois usamos o título "ADR Template" na página inicial (veja acima) diferente do previsto no template -->
<!-- markdownlint-disable-next-line MD025 -->
# {título curto do problema resolvido e solução}

## Contexto e declaração do problema

{Descreva o contexto e a definição do problema, por exemplo, de forma livre usando duas a três frases ou na forma de uma história ilustrativa.
  Você pode articular o problema na forma de uma pergunta e adicionar links para painéis de colaboração ou sistemas de gerenciamento de problemas.}

<!-- Este é um elemento opcional. Sinta-se à vontade para remover. -->
## Motivadores de decisão

* {motriz de decisão 1, por exemplo, uma força, enfrentando preocupação,…}
* {motriz de decisão 2, por exemplo, uma força, enfrentando preocupação,…}
* … <!-- o número de drivers pode variar -->

## Opções consideradas

* {título da opção 1}
* {título da opção 2}
* {título da opção 3}
* … <!-- o número de opções pode variar -->

## Resultado da decisão

Opção escolhida: "{título da opção 1}", pois
{justificação. por exemplo, única opção que atende k.o. critério de decisão condutor | que resolve força {força} | … | sai melhor (veja abaixo)}.

<!-- Este é um elemento opcional. Sinta-se à vontade para remover. -->
### Consequências

* Bom, porque {consequência positiva, por exemplo, melhoria de uma ou mais qualidades desejadas,…}
* Ruim, porque {consequência negativa, por exemplo, comprometer uma ou mais qualidades desejadas,…}
* … <!-- o número de consequências pode variar -->

<!-- Este é um elemento opcional. Sinta-se à vontade para remover. -->
## Validação

{descrever como a implementação/conformidade com o ADR é validada. Por exemplo, por uma revisão ou um teste ArchUnit}

<!-- Este é um elemento opcional. Sinta-se à vontade para remover. -->
## Prós e Contras das Opções

### {título da opção 1}

<!-- Este é um elemento opcional. Sinta-se à vontade para remover. -->
{exemplo | descrição | ponteiro para mais informações | …}

* Bom, porque {argumento a}
* Bom, porque {argumento b}
<!-- use "neutro" se o argumento fornecido não pesa nem para o bem nem para o mal -->
* Neutro, porque {argumento c}
* Ruim, porque {argumento d}
* … <!-- o número de prós e contras pode variar -->

### {título da outra opção}

{exemplo | descrição | ponteiro para mais informações | …}

* Bom, porque {argumento a}
* Bom, porque {argumento b}
* Neutro, porque {argumento c}
* Ruim, porque {argumento d}
*…

<!-- Este é um elemento opcional. Sinta-se à vontade para remover. -->
## Mais Informações

{Você pode querer fornecer evidências/confiança adicionais para o resultado da decisão aqui e/ou
  documentar o acordo da equipe sobre a decisão e/ou
  definir quando esta decisão, quando e como a decisão deve ser realizada e se/quando deve ser revista e/ou
  como a decisão é validada.
  Links para outras decisões e recursos também podem aparecer aqui.}
