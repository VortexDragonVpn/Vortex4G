{
  "Version": "1.0.1",
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
      "Name": "VIVO",
      "FLAG": "vivo",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: mentalista[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "celular.vivo.com.br",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "VIVO",
      "FLAG": "vivo",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: mentalista[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "104.18.7.80",
      "ProxyPort": "80",
      "Info": "Proxy"
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
      "Name": "VIVO",
      "FLAG": "vivo",
      "Payload": "GET wss://money-staging.infinitepay.io/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]Connection: Keep- Vivo[crlf][crlf]",
      "SNI": "money-staging.infinitepay.io",
      "TlsIP": "104.18.7.80",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "VIVO",
      "FLAG": "vivo",
      "Payload": "GET wss://carrinho-pos-familia.vivo.com.br// HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf] ]Conexão: Keep-Alive[crlf][crlf]",
      "SNI": "carrinho-pos-familia.vivo.com.br",
      "TlsIP": "",
      "ProxyIP": "104.18.6.80",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "💙TIM [SSL 5]",
      "FLAG": "tim",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "[app_host]",
      "TlsIP": "104.16.51.111",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "💚VIVO [DIRECT 1]",
      "FLAG": "vivo",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "104.18.7.80",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "💚VIVO [DIRECT 2]",
      "FLAG": "vivo",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "vigia.vivo.com.br",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "💚VIVO [SSL 1]",
      "FLAG": "vivo",
      "Payload": "GET wss://money-staging.infinitepay.io/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "money-staging.infinitepay.io",
      "TlsIP": "104.18.7.80",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "💚VIVO [SSL 2]",
      "FLAG": "vivo",
      "Payload": "GET wss://carrinho-pos-familia.vivo.com.br// HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "carrinho-pos-familia.vivo.com.br",
      "TlsIP": "104.18.6.80",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "💚VIVO [SSL 3]",
      "FLAG": "vivo",
      "Payload": "GET wss://portaljud.vivo.com.br// HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "portaljud.vivo.com.br",
      "TlsIP": "104.18.7.80",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "❤️CLARO [SSL 1]",
      "FLAG": "claro",
      "Payload": "GET wss://atendimento.descomplica.com.br HTTP/1.1[crlf]Host: [app_host][crlf]Connection: upgrade[crlf]Upgrade: websocket [crlf][crlf]",
      "SNI": "atendimento.descomplica.com.br",
      "TlsIP": "no.descomplica.com.br",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "❤️CLARO [SSL 2]",
      "FLAG": "claro",
      "Payload": "GET wss://atendimento.descomplica.com.br HTTP/1.1[crlf]Host: [app_host][crlf]Connection: upgrade[crlf]Upgrade: websocket [crlf][crlf]",
      "SNI": "atendimento.descomplica.com.br",
      "TlsIP": "714341g41.secure0121.hubspot.net",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "❤️CLARO [SSL 3]",
      "FLAG": "claro",
      "Payload": "GET wss://atendimento.descomplica.com.br HTTP/1.1[crlf]Host: [app_host][crlf]Connection: upgrade[crlf]Upgrade: websocket [crlf][crlf]",
      "SNI": "atendimento.descomplica.com.br",
      "TlsIP": "199.60.103.228",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "💛OI [SSL 1]",
      "FLAG": "oi",
      "Payload": "GET ws://www.hbogo.com.br HTTP/1.1\nHost: [app_host]\nUpgrade: ws\n\n",
      "SNI": "www.hbogo.com.br",
      "TlsIP": "www.hbogo.com.br",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "💛OI [SSL 2]",
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
