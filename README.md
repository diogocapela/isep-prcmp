# isep-prcmp

## Escalonamento

### Finalidade/Objectivo

- Dividir a capacidade de processamento da UCP (unidade central de processamento) entre vários processos
- Diminuir o tempo de resposta (sistemas de tempo-real)

### Tipos de Escalonamento

Preemptivo | Não-preemptivo
------------ | -------------
O escalonador **só** pode efetuar a comutação entre processos quando o processo **termina** ou passa para o estado de _**waiting**_. | O escalonador pode interromper a execução de um processo **sem que este tenha terminado**.
**Vantagens:** Não há possibiliade de inconsistência de dados no tratamento de vários processos. | **Vantagens:** Não há bloqueio quando corre vários processos.
**Desvantagens:** Bloqueio/lentidão no processamento. | **Desvantagens:** Dados potencialmente inconsistentes no tratamento de vários processos.

### Algoritmos de Escalonamento

- **Shortest-Job-First (SJF)**

- **Round-Robin (RR)**
  - Especialmente adaptado para **sistemas partilhados multiutilizador**.
  - Melhor tempo de resposta do que no SJF (shortest-job-first).
  - O escalonamento em RR pode ser visto como dividir a capacidade de processamento da UCP pelo vários processos.


- First-Came, First-Served (FCFS)

• Escalonamento por Prioridades

• Multi-nível por Filas
