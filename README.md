# ES46A_Exercicio1

Arquitetura em Camadas

Neste repositório se encontra um sistema simples de média ponderada.

UI (HTML, GUI Java Applets e Servlets, Java Swing)              
    |                                           |
Negócio                                    Comunicação(Java RMI)
    |                                           |
Dados (Java JDBC)                          Negócio
                                                |
										   Dados (Java JDBC)
										   
										   
Acrescentar uma página inicial com duas navegações (cálculo de médias, exibir lista)
Acrescentar uma camada de persistência que guarda as médias calculadas. 
Exibir as médias calculadas em uma nova página (lista)