# Painel de acompanhamento de fundos

Painel web que recalcula variação diária, rentabilidade acumulada e % do CDI de fundos de investimento a cada nova cota informada.

Link para testar: https://is4-tech.github.io/painel-fundos

> Todos os dados são fictícios, criados só para demonstração. O projeto foi inspirado numa rotina de acompanhamento de fundos na Tesouraria, mas não usa nenhum dado real.

## Problema

Acompanhar vários fundos exige recalcular, todo dia, variação, acumulado e comparação com o CDI. Fazer isso à mão é lento e sujeito a erro.

## O que o painel faz

- Mostra três fundos fictícios, com cota, variação do dia, acumulado, CDI acumulado e % do CDI
- Calcula tudo de novo quando você adiciona a cota do dia
- Traz um gráfico do fundo contra o CDI
- Tem uma coluna de check que refaz o acumulado por outro caminho e compara com o cálculo direto, como validação dupla

## Como foi feito

Protótipo criado com apoio de IA (vibe coding) e revisado por mim. É um único arquivo HTML, com JavaScript, sem backend.

Premissa: CDI fixo de 0,0551% ao dia útil (valor ilustrativo).

## Ferramentas

HTML · JavaScript · Vibe coding
