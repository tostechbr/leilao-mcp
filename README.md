# leilão-mcp

Uma base de imóveis de leilão e venda direta que se atualiza sozinha — e, em
cima dela, a análise que decide se um imóvel vale ou não.

Toda madrugada a lista pública de imóveis é recolhida e comparada com a da
véspera: o que entrou, o que mudou de preço, o que saiu. Imóvel que sai do ar
não desaparece — fica marcado como encerrado, com o histórico do que custava.

A análise de um imóvel específico vai do link à decisão: quanto vale a região,
quanto sobra depois de custo e reforma, e o que a matrícula, o edital e os
processos do antigo dono dizem antes de dar lance.

## Estado

| | |
|---|---|
| Imóveis na base | ~25 mil |
| Cobertura | nacional |
| Atualização | diária, automática |

## Evolução

Cada marco vira uma [release](../../releases). A versão fala do produto, não do
código — sobe quando muda o que dá pra fazer, não quando o código muda.

- `0.0.x` — a base: recolher, não duplicar, cobrir o país
- `0.1.0` — perguntar direto no Claude e no ChatGPT
- `1.0.0` — quando alguém além de mim usa todo dia
