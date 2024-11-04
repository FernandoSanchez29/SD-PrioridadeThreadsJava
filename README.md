# SD-PrioridadeThreadsJava

O sistema cria duas Threads, uma com alta prioridade e outra com baixa prioridade.
A Thread de alta prioridade tem preferência sobre a de baixa prioridade, fazendo com que ela execute primeiro, porém a Thread de baixa prioridade executa em maior quantidade de vezes devido a Thread de alta prioridade aguardar por 10 milesegundos antes de executar novamente.
As execuções intercalam de acordo com escalanador.
