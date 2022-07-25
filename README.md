{
  "Version": "1.0.1",
  "ReleaseNotes": "Nova Atualização Disponível",
  "UrlUpdate": "https://raw.githubusercontent.com/VortexDragonVpn/Vortex4G/main/README.md",
  "Sms": "https://raw.githubusercontent.com/VortexDragonVpn/Vortex4G_sms_inicial/main/README.md",
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
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: mentalista[crlf][crlf]"
      "TlsIP": "",
      "ProxyIP": "celular.vivo.com.br",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "?VIVO FAST",
      "FLAG": "vivo",
      "Payload": "GET wss://carrinho-pos-familia.vivo.com.br// HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "carrinho-pos-familia.vivo.com.br",
      "TlsIP": "104.18.6.80",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "VIVO",
      "FLAG": "vivo",
      "Payload": "GET wss://api.bitso.com/ HTTP/1.1[lf]Host: [app_host][lf]Proxy-Connection: Keep-Alive[lf]User-Agent: [ua][lf] Conexão: upgrade[lf]Upgrade: websocket[lf]Sec-Websocket-Extensions: superspeed[lf][lf]",
      "SNI": "api.bitso.com",
      "TlsIP": "172.64.195.2",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "?VIVO NETFLIX",
      "FLAG": "vivo",
      "Payload": "GET wss://support.uptodown.com/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "support.uptodown.com",
      "TlsIP": "162.159.136.63",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "VIVO NEXT",
      "FLAG": "vivo",
      "Payload": "GET wss://help.pornhub.com// HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "help.pornhub.com",
      "TlsIP": "162.159.135.63",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "️CLARO GO",
      "FLAG": "claro",
      "Payload": "GET wss://go.kaltura.com HTTP/1.1[crlf]Host: [app_host][crlf]Connection: upgrade[crlf]Upgrade: websocket [crlf][crlf]",
      "SNI": "go.kaltura.com",
      "TlsIP": "go.kaltura.com",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "️CLARO ZIP",
      "FLAG": "claro",
      "Payload": "GET wss://4.icanhazip.com HTTP/1.1[crlf]Host: [app_host][crlf]Connection: upgrade[crlf]Upgrade: websocket [crlf][crlf]",
      "SNI": "4.icanhazip.com",
      "TlsIP": "4.icanhazip.com",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "TIM 2", 
      "FLAG": "tim", 
      "Payload": "GET wss://static.r4you.co HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]", 
      "SNI": "static.r4you.co", 
      "TlsIP": "104.26.5.175", 
      "ProxyIP": "", 
      "ProxyPort": "443", 
      "Info": "Tlsws"
    }, 
    { 
      "Name": "TIM 3", 
      "FLAG": "tim", 
      "Payload": "GET wss://static.r4you.co HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]", 
      "SNI": "static.r4you.co", 
      "TlsIP": "104.26.4.175", 
      "ProxyIP": "", 
      "ProxyPort": "443", 
      "Info": "Tlsws"
    },
    {     
      "Name": "️CLARO",
      "FLAG": "claro",
      "Payload": "GET wss://atendimento.descomplica.com.br HTTP/1.1[crlf]Host: [app_host][crlf]Connection: upgrade[crlf]Upgrade: websocket [crlf][crlf]",
      "SNI": "atendimento.descomplica.com.br",
      "TlsIP": "199.60.103.228",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    }, 
    {
      "Name": "OI GO",
      "FLAG": "oi",
      "Payload": "GET ws://www.hbogo.com.br HTTP/1.1\nHost: [app_host]\nUpgrade: ws\n\n",
      "SNI": "www.hbogo.com.br",
      "TlsIP": "www.hbogo.com.br",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "OI HB",
      "FLAG": "oi",
      "Payload": "GET ws://www.hbogo.com.br HTTP/1.1\nHost: [app_host]\nUpgrade: ws\n\n",
      "SNI": "www.hbogo.com.br",
      "TlsIP": "104.16.53.91",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    }
  ]
}
