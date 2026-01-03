03/01/2026 - O Desafio da Integridade Física
O que aprendi: Descobri que arquivos executáveis podem ter dados extras no final chamados Overlays.

Problema: Ao salvar o código modificado, o arquivo perdia esses dados e não abria.

Solução: Usei o comando binário copy /b para "colar" o código novo no corpo antigo, restaurando a funcionalidade.
