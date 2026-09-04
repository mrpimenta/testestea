# Mapa Neurocognitivo — `testestea`

Aplicação web estática para estudo de avaliação neuropsicológica e rastreio. O projeto agora possui duas áreas separadas:

- `index.html`: mapa exploratório com tarefas autorais de raciocínio, atenção, funções executivas, memória, linguagem, história do desenvolvimento e autorrelato;
- `padronizados.html`: instrumentos padronizados cuja reprodução eletrônica é compatível com as permissões publicadas pelos detentores.

## Instrumentos padronizados implementados

### AQ-10 — Adulto

Versão curta do Autism Spectrum Quotient para adultos, em português do Brasil. Pontuação de 0 a 10, com referência de 6 ou mais para considerar encaminhamento para avaliação diagnóstica especializada. Não é diagnóstico.

Fonte: Autism Research Centre, University of Cambridge. A instituição informa que o AQ-10 pode ser usado gratuitamente para pesquisa e educação não comercial, com atribuição e sem alteração do instrumento.

https://www.autismresearchcentre.com/tests/autism-spectrum-quotient-10-items-aq-10-adult/

### ASRS-v1.1 — Screener de 6 itens

Rastreio de TDAH em adultos, janela de seis meses. O projeto usa a pontuação de pesquisa 0–24 publicada na atualização de 2024: 0–9 negativo baixo; 10–13 negativo alto; 14–17 positivo baixo; 18–24 positivo alto.

A página oficial informa que o screener de 6 itens pode ser reproduzido sem pedido formal de permissão desde que o instrumento não seja alterado, sejam mantidas as opções de resposta e seja incluída a atribuição correspondente.

https://www.hcp.med.harvard.edu/ncs/asrs.php

### PHQ-9

Rastreio e graduação de sintomas depressivos nas últimas duas semanas. Escore 0–27, com faixas usuais mínima, leve, moderada, moderadamente grave e grave.

O PHQ-9 é © Pfizer Inc.; os termos publicados informam que não é necessário pedir permissão para reproduzir, traduzir, exibir ou distribuir o instrumento.

https://www.phqscreeners.com/

### GAD-7

Rastreio e graduação de sintomas de ansiedade nas últimas duas semanas. Escore 0–21, com faixas mínima, leve, moderada e grave.

O GAD-7 é © Pfizer Inc.; os termos publicados informam que não é necessário pedir permissão para reproduzir, traduzir, exibir ou distribuir o instrumento.

https://www.phqscreeners.com/

## Instrumentos que não foram copiados

O fato de este projeto ser educacional ou de estudo não elimina direitos autorais, requisitos de licença ou regras de segurança de testes. Por isso não reproduzimos integralmente:

- WAIS, WISC e outras escalas Wechsler;
- SRS-2;
- BDI-II;
- MINI;
- AC15 e outros instrumentos cujo conteúdo/material seja restrito.

Quando uma área cognitiva não possui instrumento livre adequado, o `index.html` usa uma tarefa autoral e deixa explícito que ela não possui normas clínicas nem substitui o teste profissional correspondente.

## Interpretação

Nenhum resultado do site confirma ou descarta diagnóstico. Os escores de instrumentos diferentes não devem ser somados nem convertidos em “percentual de autismo”, “percentual de TDAH” ou probabilidade diagnóstica.

No PHQ-9, qualquer resposta diferente de zero no item sobre pensamentos de morte ou autoagressão gera um aviso adicional na interface. Isso não é uma avaliação de risco completa.

## Privacidade

Não há backend. As respostas são armazenadas somente no `localStorage` do navegador utilizado. Limpar os dados do navegador apaga o histórico salvo.

## Como executar

Não há dependências. Abra `index.html` ou `padronizados.html` em um navegador moderno.

Para publicar pelo GitHub Pages, use **Settings → Pages** e configure a publicação a partir da branch `main` e pasta raiz (`/`).

## Uso profissional

No Brasil, aplicação, correção e interpretação profissional de testes psicológicos deve observar a regulamentação do Conselho Federal de Psicologia e o SATEPSI, inclusive as condições específicas de informatização de cada instrumento.

Referências gerais:

- SATEPSI: https://satepsi.cfp.org.br/
- CFP: https://site.cfp.org.br/
- NICE CG142 — autismo em adultos: https://www.nice.org.uk/guidance/cg142
