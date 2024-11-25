# OPNsense



## Interfaces

    settings

        [*] Disable

        hardware checksum offload 
        #Permite que a placa de rede calcule automaticamente os checksums de pacotes TCP, UDP e IP, reduzindo a carga de trabalho na CPU 

        hardware TCP segmentation offload
        #Permite que a placa de rede divida grandes blocos de dados (offload) em pacotes menores de TCP, reduzindo a carga na CPU. 

        hardware large receive offload
        #Combina vários pacotes recebidos em um único bloco grande antes de enviá-lo à CPU, otimizando o uso do processador. 