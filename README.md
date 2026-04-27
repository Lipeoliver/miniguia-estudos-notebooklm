	O meu notebooklm, foi criado pensando em fundamentos basicos de 
rede de computadores.

os links utilizados foram os seguintes

https://www.youtube.com/watch?v=BSe7EgvDB6Q 
https://www.youtube.com/watch?v=p1wdm_hkAY8 
https://www.youtube.com/watch?v=yLgansF_h1w 
https://www.youtube.com/watch?v=7pU9iHoJRm4 
https://www.youtube.com/watch?v=i4KMcl0tuEg 
https://www.youtube.com/watch?v=dp9ynjJamoI&list=PLuf64C8sPVT_nObvAFU5W-SiE04ST-PlL 
https://www.youtube.com/watch?v=G9VlDTshk-k 
https://www.youtube.com/watch?v=hwttZtWkXTk 
https://www.youtube.com/watch?v=vGuqKIRWosk 
https://www.youtube.com/watch?v=anFV6z8pEVU&list=PLAp37wMSBouBnNup2tD-mC36JT96vHBZy 
https://www.youtube.com/watch?v=enrOK-OkZrQ

textos utilizados 
https://aws.amazon.com/pt/compare/the-difference-between-https-and-http/ 
https://www.cloudflare.com/pt-br/learning/ddos/glossary/hypertext-transfer-protocol-http/ 
https://www.cloudflare.com/pt-br/learning/ssl/what-is-https/ 
https://www.fortinet.com/br/resources/cyberglossary/network-address-translation 
https://www.cisco.com/c/pt_br/support/docs/ip/network-address-translation-nat/13772-12.html 
https://www.reddit.com/r/InternetBrasil/comments/1devzc5/o_que_%C3%A9_nat/ 
https://www.cisco.com/c/pt_br/support/docs/security/vpn-3000-series-concentrators/7210-vrrp.pdf 
https://www.dell.com/support/kbdoc/pt-br/000121369/como-configurar-roteador-virtual-redundancy-protocol-vrrp-on-dell-emc-networking-os9-switches 
https://cloud.google.com/dns?utm_source=google&utm_medium=cpc&utm_campaign=latam-BR-all-pt-dr-SKWS-all-all-trial-e-dr-1710136-LUAC0016089&utm_content=text-ad-none-any-DEV_c-CRE_788588004462-ADGP_Hybrid+%7C+SKWS+-+EXA+%7C+txt+-+Infrastructure-Networking-Cloud+DNS-BR-KWID_300856343021-kwd-300856343021&utm_term=KW_dns-ST_DNS&gclsrc=aw.ds&gad_source=1&gad_campaignid=23370737483&gclid=Cj0KCQjw77bPBhC_ARIsAGAjjV_UYbcz3YvHIW-FGql7Mv_f8mOuSZVYCvJmjqXSuC5iu7IdfK8iHuoaAknrEALw_wcB 
https://www.cloudflare.com/pt-br/learning/dns/what-is-dns/ 
https://www.ibm.com/br-pt/think/topics/dns 
https://www.google.com/search?q=DHCP&rlz=1C1VDKB_pt-PTBR1003BR1003&oq=DHCP&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIGCAEQRRg90gEIMTc1NmowajSoAgCwAgA&sourceid=chrome&ie=UTF-8 
https://www.fortinet.com/br/resources/cyberglossary/dynamic-host-configuration-protocol-dhcp 
https://www.ibm.com/docs/pt-br/i/7.5.0?topic=protocol-dhcp-concepts 
https://www.cloudflare.com/pt-br/learning/ddos/glossary/open-systems-interconnection-model-osi/ 
https://aws.amazon.com/pt/what-is/osi-model/ 
https://www.ibm.com/br-pt/think/topics/osi-model 
https://www.fortinet.com/br/resources/cyberglossary/file-transfer-protocol-ftp-meaning 
https://www.ibm.com/docs/pt-br/aix/7.3.0?topic=f-ftp-command 

Pergunta realizada
qual e a porta do ssh

resposta
A porta padrão utilizada pelo protocolo SSH (Secure Shell) é a 22
.
O SSH é um protocolo utilizado para o acesso e administração remota de dispositivos, como servidores e ativos de rede, de forma segura e criptografada
. Nas configurações de rede e segurança, como em firewalls ou proxies, o tráfego destinado à porta 22 é identificado como tráfego SSH para permitir ou monitorar conexões remotas seguras

pergunta realizada
para que serve o dhcp

resposta

O DHCP (Dynamic Host Configuration Protocol) é um protocolo de rede da camada de aplicação utilizado para atribuir endereços IP e outras configurações de conectividade de forma automática aos dispositivos (clientes) de uma rede
. Ele é o sucessor do protocolo BOOTP e serve para eliminar a necessidade de configuração manual ou estática de cada estação de trabalho
.
As principais funções e características do DHCP descritas nas fontes são:
Automação de Configurações: O DHCP fornece informações fundamentais para que um dispositivo consiga se comunicar, incluindo o endereço IP único, a máscara de rede, o gateway padrão e os servidores DNS
.
Gerenciamento de IPs: O servidor DHCP utiliza um "Escopo", que define faixas de endereços planejadas para distribuição, permitindo também configurar exclusões e reservas de IPs específicos
.
Ciclo de Vida (Lease): Os endereços não são entregues permanentemente; eles possuem um período de concessão (alocação), podendo ser renovados pelo cliente conforme a necessidade
.
Processo de Comunicação: O funcionamento ocorre em quatro etapas principais:
DHCPDISCOVER: O cliente envia uma requisição para a rede buscando um servidor
.
DHCPOFFER: O servidor DHCP responde oferecendo uma configuração
.
DHCPREQUEST: O cliente solicita formalmente a configuração oferecida
.
DHCPACK: O servidor confirma e envia os parâmetros finais de rede
.
Para que o serviço funcione, o servidor DHCP deve obrigatoriamente possuir um IP fixo
. As fontes também alertam para uma vulnerabilidade de segurança: a presença de servidores DHCP maliciosos ou configurados por engano na mesma rede, que podem enviar informações incorretas aos clientes e impedir o acesso à internet ou interceptar comunicações
