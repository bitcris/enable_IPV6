#Habilitar IPv6 | 12/11/2023
Esse repositório é um pequeno tutorial sobre como ativar o protocolo IPv6 em dispositivos conectados em redes de provedores que não tem suporte ao IPv6.

<b>PRIMEIRO VAMOS VERIFICAR SE A REDE EM QUE ESTAMOS CONECTADOS TEM IPV6 HABILITADO E FUNCIONAL</b><br>
Acesse: https://cafeware.vercel.app/myipv6
<br>
Verifique se a opção IPV6 está marcada como <b>"OK"</b><br><br>
Caso contrário aparecerá <b>"Unavaliable"</b> e possívelmente sua rede não tem IPv6 habilitado pelo provedor.
<br><br>
<b>PARA HABILITAR MANUALMENTE VAMOS BAIXAR O CLOUDFLARE WARP</b><br>
Acesse: https://1.1.1.1/
<br>

Instale o aplicativo de acordo com o seu dispositivo/sistema <br>
O aplicativo está atualmente disponível para: <br>
<b>App Store</b><br>
<b>Google Play</b><br>
<b>MacOs</b><br>
<b>Windows</b><br>
<b>Linux</b><br>
<br>

<b>IMPORTANTE</b><br>
Este aplicativo cria uma conexão encriptada com VPN
e altera os servidores de DNS para os servidores da Cloudflare.
Para alterar apenas o seu DNS padrão para o DNS da Cloudflare, use o modo normal do alicativo
sem habilitar o modo <b>WARP</b><br>
E para encriptar a conexão e Habilitar o IPv6, use com o modo <b>WARP</b> habilitado.
<br>

<b>TESTANDO O IPv6</b>
Para verificar se o IPv6 foi habilitado volte a acessar
https://cafeware.vercel.app/myipv6
<br>
Verifique se a opção IPv6 aparece "OK"
<br>

Usar o aplicativo com o modo WARP habilitado também irá passar todo o tráfego por um nó da Cloudflare, normalmente um servidor mais próximo de sua localização.
Para verificar isso, você pode acessar:<br>https://cafeware.vercel.app <br>
e ver onde este servidor se encontra.
