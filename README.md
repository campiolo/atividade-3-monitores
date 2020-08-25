# Atividade 03  - Monitores

1. Escreva uma monitor Counter que possibilita um processo
dormir até o contador alcançar um valor. A classe Counter
permite duas operaçõess: increment() e sleepUntil(int x).

2. Escreva um monitor BoundedCounter que possui um valor
mínimo e máximo. A classe possui dois métodos: increment()
e decrement(). Ao alcançar os limites mínimo ou máximo, a
thread que alcançou deve ser bloqueada.

3. Implemente uma solução para o problema do Barbeiro
Dorminhoco usando monitores. Para o problema, considere uma barbearia que possui: 1 barbeiro, 1 cadeira de barbeiro, N cadeiras para os clientes aguardarem. Se não tiver cliente, o barbeiro senta na sua cadeira e dorme; se um cliente chega e barbeiro está dormindo, ele acorda o barbeiro; se cliente chega e barbeiro ocupado, aguardam nas cadeiras de espera ou, se não houver cadeira vazia, vão embora.
