# TS-REDES-II
O projeto 1 está em pausa devido aos bugs do Packet Tracer. 

O projeto 2 é o projeto atual. 

<img width="1086" height="444" alt="23-07cort" src="https://github.com/user-attachments/assets/200bcbf8-ca92-4702-abdf-884e246f4e1b" />

Projeto de Infraestrutura de Redes para Campus Universitário
Recentemente, desenvolvi um projeto de infraestrutura de rede voltado para um ambiente universitário, o objetivo é promover boa disponibilidade, segmentação e segurança.

Tecnologias e Implementações:

Inter-VLAN Routing & SVI: Segmentação em 5 sub-redes/VLANs operacionais para isolamento de tráfego;

Redundância & Agregação de Link: Implementação de EtherChannel com protocolo LACP para maior largura de banda e eficiência no tráfego de distrribuição;

Serviços de Rede: Alocação dinâmica de endereçamento via DHCP gerenciado por um servidor dedicado (com suporte a IP Helper-Address);

Infraestrutura Sem Fio (Wi-Fi): Configuração dupla, um segmento operando em modo Access Point (Bridge) para a rede Admin e outro em modo Gateway com NAT para isolamento de dispositivos na rede LAB. 

Desafios & Troubleshooting:
Integração do Home Router (NAT): Consegui lidar com as limitações e comportamentos do Packet Tracer ao ajustar a interface WAN para endereçamento IP Estático.

Configuração de EtherChannel no Layer 3: Resolução de inconsistências de nomenclatura e alinhamento de parâmetros entre o Switch L3 e os switches de acesso.

Próximos passos: A ideia agora é expandir a topologia implementando um laboratório dedicado exclusivamente a IPv6 (Dual-Stack / SLAAC).
