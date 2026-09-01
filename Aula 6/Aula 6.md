## 01/09

### Qual o endereço de rede e de broadcast do IP 172.38.50.213 na /26 
    - Sabe-se que esse IP esta no meio pois o ultimo numero da rede deve ser multiplo de 64 (que é o numero de IP's possíveis na /26)
    - E o broadcast deve ser multiplo de 64 - 1 

    - 172.38.50.192 > 172.38.50.255

### 192.168.23.54 - /28
    - R: 192.168.23.48
    - B: 192.168.23.63

### 10.190.2.34 - /26 
    - R: 10.190.2.0
    - B: 10.190.2.63

### 200.3.120.222 - /29
    - R: 200.3.120.216
    - B: 200.3.120.223

### 244.30.103.67 - /27 
    - R: 244.30.103.64
    - B: 244.30.103.95

### 172.0.21.17 - /28 
    - R: 172.0.21.16
    - B: 172.0.21.31

### 208.54.21.16 - /23
    - R: 200.54.20.0
    - B: 200.54.21.255  -> no .20 cabem 256 IP's e no 21 também, então seria como somar 256 + 256 que fecharia os 512 da /23 
\