# Mapa Neurocognitivo — `testestea`

Aplicação web estática para organizar, de forma exploratória, desempenho em tarefas breves e autorrelato em áreas frequentemente investigadas em avaliação neuropsicológica.

## O que existe na versão 0.1

- raciocínio lógico e verbal;
- atenção;
- funções executivas;
- memória;
- linguagem e pragmática;
- traços sociais e características associadas ao TEA;
- sinais associados ao TDAH;
- ansiedade e humor como fatores de contexto;
- tendências de personalidade/comportamento;
- história do desenvolvimento desde a infância;
- resultados separados entre **tarefas de desempenho** e **autorrelato/história**;
- salvamento apenas no `localStorage` do navegador;
- impressão do resumo pelo próprio navegador.

## Limites importantes

Este projeto **não é um teste psicológico padronizado**, não calcula QI, não produz percentis normativos e não diagnostica TEA, TDAH, depressão, ansiedade ou qualquer outra condição.

Os itens implementados são originais e não reproduzem conteúdo de instrumentos proprietários ou de uso profissional restrito, como escalas Wechsler, SRS-2, AC15 e outros testes psicológicos padronizados.

No Brasil, a aplicação, correção e interpretação profissional de testes psicológicos deve observar a regulamentação do Conselho Federal de Psicologia e o SATEPSI, inclusive quanto à autorização de formatos informatizados/remotos.

Referências úteis:

- SATEPSI: https://satepsi.cfp.org.br/
- CFP — Resolução nº 31/2022 e orientações sobre avaliação psicológica: https://site.cfp.org.br/
- NICE — identificação e avaliação de autismo em adultos: https://www.nice.org.uk/guidance/cg142

## Como executar

Não há dependências. Abra `index.html` em um navegador moderno.

Para publicar pelo GitHub Pages, use **Settings → Pages** e configure a publicação a partir da branch `main` e pasta raiz (`/`).

## Próximos passos sugeridos

1. adicionar tarefas realmente temporizadas de atenção e inibição;
2. criar uma etapa de memória com apresentação/ocultação controlada dos estímulos;
3. permitir registrar exemplos concretos e impacto funcional em cada domínio;
4. gerar relatório estruturado em PDF para levar ao profissional;
5. adicionar modo “informante/familiar” para história do desenvolvimento;
6. criar versionamento dos itens e trilha de alterações;
7. revisar linguagem, acessibilidade e validade de conteúdo com psicólogo/neuropsicólogo antes de qualquer uso clínico ou de pesquisa.

## Privacidade

A versão atual não possui backend. As respostas ficam somente no navegador utilizado. Isso reduz a exposição de dados, mas significa que limpar os dados do navegador apaga o histórico salvo.