
OSI model in networks

TCP vs UDP
1. https://www.freecodecamp.org/news/tcp-vs-udp/

REST, HTTP, RPC 
1. https://stackoverflow.com/questions/2190836/what-is-the-difference-between-http-and-rest
2. HTTP is a transfer protocol (Layer 7 of OSI). REST enforces how to use HTTP (HTTP can be misused with rules enforced by REST).
4. In RPC, the interaction happens via a client-server stub (via a intermediate object). RPC is action-oriented and REST is resource oriented.
5. https://stackoverflow.com/questions/7356884/whats-the-difference-between-rpc-and-browser-server

HTTP vs TCP
1. TCP is layer 4 and HTTP is layer 7 in OSI. HTTP uses TCP internally. 
2. https://stackoverflow.com/questions/23157817/http-vs-tcp-ip-send-data-to-a-web-server 

HTTP vs HTTPS
1. HTTPS is a layer of TLS over TCP
2. HTTPS uses TLS/SSL for encryption of data and authentication of server (TLS is upgraded version of SSL)
3. HTTPS basically involves setting up a tunnel/connection (like that in HTTP), validating the certicates and encrypting the data during transfer  
4. How to create HTTPS version of a URL? - 
  - Generate a keystore (say Java keystore)
  - Create CSR (Certificate Signing Request) 
  - Use this CSR file to create a domain certificate 
  - Chain domain cerificate with root and issuing authority 
  - Upload chained certificate to the keystore
  - Use this keystore into your web server configuration to validate HTTPS url

TLS vs mTLS
  - TLS which does client authentication as well
  - https://www.cloudflare.com/en-gb/learning/access-management/what-is-mutual-tls/

HTTP1 vs HTTP2 vs WebSockets
  - https://www.cloudflare.com/en-gb/learning/performance/http2-vs-http1.1/
  - https://stackoverflow.com/questions/28582935/does-http-2-make-websockets-obsolete

Webhook vs Websocket
  - https://stackoverflow.com/questions/23172760/differences-between-webhook-and-websocket

[To-do]REST vs GraphQL 
[To-do]REST vs gRPC
