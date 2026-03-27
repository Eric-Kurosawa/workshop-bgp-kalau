# Workshop BGP
**Lab feito no EVE-NG do Workshop de BGP ministrado pelo Gustavo Kalau**

<br>

**Passos realizados:**
1. Configuração do eBGP nos Roteadores R3, R7 e R8
2. Configuração do eBGP nos Roteadores R4, R5, R6 e R9
3. Divulgação dos prefixos dos Roteadores R6 e R7 e verificação das rotas
4. Configuração do iBGP entre os Roteadores R8, R9 e R10
5. Resolução do problema do next-hop nos roteadores R8 e R9
6. Resolução do problema de iBGP entre os Roteadores R8, R9 e R10 e divulgação do prefixo do Roteador R10
7. Configuração do OSPF na rede CHARMANDER CORP (Laranja)
8. Configuração do Router Reflector e Update Source (R1 - R5)
9. Configuração do Peer Group e remoção da configuração que estava sobrando no Roteador R1
10. Divulgação dos prefixos 1.10.10.0/24 e 1.10.20.0/24 do Roteador R1 no BGP
11. Divulgação da rota agregada 1.10.0.0/16 via Roteador R1
12. Engenharia de tráfego: influenciar o upload manipulando o atributo Weight do Roteador R8
13. Engenharia de tráfego: influenciar o upload manipulando o atributo Local Preference do Roteador R8
14. Engenharia de tráfego: influenciar o download nos Roteadores R3, R4 e R5 (e remoção do route-map IN do Roteador R8)
15. Engenharia de tráfego: evitar o trânsito pelo AS12345 nos Roteadores R3, R4 e R5
