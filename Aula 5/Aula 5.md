## 25/08

### A camada de rede 
    - Responsável pelo endereçamento da mensagem que vai ser enviada 
    - Transferencia da origem para o destino 
    - Ela ja sabe quem é a origem e quem é o destino 

### Roteador
    - Armazena a mensagem que chegou até chegar o restante, dai sim ele transfere para o proximo 

### Tabela de rotas 
    - Aqui que todo mundo sabe o que é todo mundo e pra onde vão 

### A camada de rede da Internet 
    - Totalmente dependete do protocolo Ipv4
        - IPv4 consiste em:
            - uma parte de cabeçalho -> 32 bits de largura 

                ---------------------------------------------------------------
                | versao | IHL | tipo de serviço |        tamanho total       |
                ---------------------------------------------------------------
                |          identificação         | flags |  desloamento flag  |
                ---------------------------------------------------------------
                |  tempo de vida   |  protocolo  |    checksum do cabeçalho   |
                ---------------------------------------------------------------
                |                    endereço ip de origem                    | 
                ---------------------------------------------------------------
                |                    endereço ip de destino                   |
                ---------------------------------------------------------------
                |                opções (se IHL for maior que 5)              |
                ---------------------------------------------------------------
                |                      dados (carga)                          |
                ---------------------------------------------------------------

            - uma parte de dados 
            
### Atividade em Aula 
    208.104.3.0  /24  -> 208.104.3.255

    LAB1 (20)                                                                            
    /27                                                                   
    208.104.3.64 > 208.104.3.95                     

    LAB2 (50)
    /26 
    208.104.3.0 > 208.104.3.63

    LAB3 (15)
    /28
    208.104.3.128 > 208.104.3.143
   
