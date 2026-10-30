# Próximos passos (treino-app)

Notas de funcionalidades pendentes/combinadas, pra qualquer sessão futura
retomar sem perder contexto.

## Registro de carga (em andamento)
- Adicionar campo de carga por exercício, salvo junto com o progresso.
- Formato: texto livre (ex: "Halteres 12kg", "Cross 15kg cabo baixo"),
  não só número — Tiago varia o equipamento do mesmo exercício
  (ex: elevação lateral ora com halteres, ora no cross).
- Pré-preencher com o último valor usado, pra ele só atualizar quando mudar.

## Versão para treino em casa (sem máquinas)
- Pedido por Tiago: ter uma versão do treino usável fora da academia
  (viagem) e para a sogra dele, que treina em casa.
- Baseado em peso corporal + elásticos, sem equipamento de academia.
- Pode ser uma página separada (ex: `/casa/index.html`), reaproveitando
  a mesma estrutura do app (ver README do método de 4 dias no index.html).
- Precisa de STORAGE_KEY própria, diferente da usada no treino principal.
