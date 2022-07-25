{
  "Version": "2.0.3",
  "ReleaseNotes": "Nova Atualização Disponível",
  "UrlUpdate": "https://raw.githubusercontent.com/VortexDragonVpn/Vortex4G/main/README.md",
  "Sms": "BOTAR LINK DO SMS AQUI",
  "EmailFeedback": "vortexssh@gmail.com",
  "UrlContato": "https://t.me/apolo_vx",
  "UrlTermos": "hhttps://raw.githubusercontent.com/VortexDragonVpn/Vortex4G_termos/main/README.md",
  "CheckUser": "true",
  "Udp": [
    {
      "Porta": "7300"
    }
  ],
  "Servers": [
    {
      "Name": "SERVIDOR PREMION",
      "TYPE": "premium",
      "FLAG": "br.png",
      "ServerIP": "vortex.dragonvpn.xyz",
      "CheckUser": "http://54.232.63.59:4343/checkUser",
      "ServerPort": "22",
      "SSLPort": "443",
      "USER": "",
      "PASS": ""
    }
  ],
  "Networks": [
    {
      "Name": "?VIVO CLOUD",
      "FLAG": "vivo", 
      "Payload": "GET wss://[rotate=recarga.vivo.com.br;live.vivo.com.br;planosvivointernet.com.br;mobile.mercadolibre.com;www.oi.com.br;developers.mercadolivre.com;www.assinenet.com.br;hire.indeed.com;accounts.descomplica.com.br;reviews.submarino.com.br] HTTP/1.1[lf]Host: [app_host][lf]Proxy-Connection: Keep-Alive[lf]User-Agent: [ua][lf]Connection: upgrade[lf]Upgrade: websocket[lf]Sec-Websocket-Extensions: superspeed[lf][lf]", 
      "SNI": "[app_host]", 
      "TlsIP": "unpkg.com", 
      "ProxyIP": "unpkg.com", 
      "ProxyPort": "80", 
      "Info": "Proxy" 
    },
    {
    "Name": "VIVO CONFIG", 
      "FLAG": "vivo", 
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf][crlf]", 
      "SNI": "", 
      "TlsIP": "[app_host]", 
      "ProxyIP": "172.67.165.43", 
      "ProxyPort": "80", 
      "Info": "Proxy"
    },
    {
    "Name": "VIVO CONFIG", 
      "FLAG": "vivo", 
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf][crlf]", 
      "SNI": "", 
      "TlsIP": "[app_host]", 
      "ProxyIP": "104.18.7.80", 
      "ProxyPort": "80", 
      "Info": "Proxy"
