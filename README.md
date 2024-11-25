# OPNsense



## Interfaces

    settings

        [*] hardware checksum offload 
        #Permite que a placa de rede calcule automaticamente os checksums de pacotes TCP, UDP e IP, reduzindo a carga de trabalho na CPU 

        [*] hardware TCP segmentation offload
        #Permite que a placa de rede divida grandes blocos de dados (offload) em pacotes menores de TCP, reduzindo a carga na CPU. 

        [*] hardware large receive offload
        #Combina vários pacotes recebidos em um único bloco grande antes de enviá-lo à CPU, otimizando o uso do processador. 

## System 

    Settings
        
        Acess
            Users
                root Disabled
        
        Geral
            [*] DNS server options
            Permitir que a lista de servidores DNS seja substituída pelo DHCP/PPP na WAN.

            [*] Gateway switching Allow default gateway switching
            Se o link onde o gateway padrão está localizado falhar, altere o gateway padrão para outro disponível.

        Adminitration
            Port HTTPS 443
            
            HTTP Redirect Disable web GUI redirect rule
            Secure Shell
                Enable Secure Shell
            Permit root user login
            Permit password login

        Authentication
            Ask password        