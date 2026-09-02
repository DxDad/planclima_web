# Notas para integração ao Liferay

Este protótipo foi construído como uma demonstração independente. No ambiente definitivo, o cabeçalho, o menu, a navegação estrutural e o rodapé devem ser fornecidos pelo próprio Liferay.

## Estrutura sugerida

### Página inicial do PlanClima SP

A página atual pode ser preservada. A única alteração necessária para a proposta é a inclusão de **Plano na Web** na navegação principal, apontando para uma nova página pública dentro do mesmo site.

### Página Plano na Web

Recomenda-se criar uma página própria para a versão web. O conteúdo central de `planclima-web.html` pode ser dividido em fragments ou conteúdos web reutilizáveis:

1. apresentação da versão web;
2. navegação local e sumário;
3. modelo de capítulo;
4. modelo de figura com legenda;
5. modelo de tabela;
6. modelo de meta e ações vinculadas;
7. navegação entre capítulos.

## CSS

Os estilos específicos foram organizados em `assets/css/styles.css`. Na integração:

- evitar seletores globais para `body`, `h1`, `table` ou `a` sem uma classe de escopo;
- manter os componentes da versão web dentro de um contêiner com classe própria, como `.planclima-web`;
- revisar quais regras já são atendidas pelo tema institucional;
- preservar foco visível, contraste, ampliação de texto e comportamento responsivo;
- evitar estilos em linha para conteúdos que serão gerenciados pela equipe editorial.

## Imagens e documentos

As imagens devem ser enviadas para **Documentos e Mídia** no Liferay e ter seus endereços atualizados no conteúdo. Para cada imagem, registrar:

- finalidade da imagem;
- texto alternativo ou indicação de imagem decorativa;
- legenda e crédito, quando aplicáveis;
- descrição detalhada para mapas, gráficos e diagramas complexos.

O PDF original deve continuar disponível como documento de referência.

## Conteúdo estruturado

Para a transposição integral, recomenda-se definir estruturas próprias para capítulos e metas. Uma ficha de meta pode conter os campos:

- número e título;
- estratégia e objetivo estratégico;
- descrição;
- indicador;
- prazo;
- secretaria responsável;
- secretarias de apoio;
- setor de mitigação;
- risco climático;
- Objetivos de Desenvolvimento Sustentável relacionados;
- ações vinculadas.

Essa estrutura permite editar e atualizar o conteúdo sem remontar manualmente cada página.

## Pontos a confirmar com a equipe responsável

- versão e configuração do Liferay;
- permissão para criação ou importação de fragments;
- possibilidade de cadastrar estruturas de conteúdo web;
- padrão institucional de endereços amigáveis;
- estratégia de busca e indexação;
- fluxo de revisão e publicação;
- responsáveis por validar descrições de conteúdos visuais complexos.

