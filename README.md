# Show da Química

Jogo no estilo Show do Milhão para estudar química orgânica para o ENEM (hidrocarbonetos e funções oxigenadas).
São 251 perguntas com moléculas desenhadas em bastão, uma escada de 16 degraus com notas ilustrativas, degraus seguros, quatro ajudas e um modo "Revisar meus erros".

É um arquivo só (`index.html`), sem dependências: abre direto no navegador. Esta é a versão minificada, sem o gancho de testes.

As notas da escada servem só de motivação. Não são um cálculo de TRI.

O arquivo é gerado por `node build-show.mjs` no projeto de origem (`anatomy-quimica`). As respostas são calculadas pelo modelo químico e conferidas por `check-show.mjs`.
