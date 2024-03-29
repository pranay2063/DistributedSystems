
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

HTTPS
1. HTTPS is a layer of TLS over TCP. HTTPS uses TLS for encryption of data and authentication of server (TLS is upgraded version of SSL).
2. HTTPS basically involves setting up a tunnel/connection (like that in HTTP), validating the certicates and encrypting the data during transfer
3. Resources to read
    - https://www.cloudflare.com/en-gb/learning/ssl/transport-layer-security-tls/
    - https://www.cloudflare.com/en-gb/learning/ssl/what-happens-in-a-tls-handshake/
    - https://www.cloudflare.com/en-gb/learning/ssl/what-is-a-session-key/
    - https://www.cloudflare.com/en-gb/learning/ssl/what-is-ssl/
    - https://www.geeksforgeeks.org/difference-between-truststore-and-keystore-in-java/
4. How to create HTTPS version of a URL? - 
    - Generate a keystore (say Java keystore)
    - Create CSR (Certificate Signing Request) 
    - Use this CSR file to create a domain certificate 
    - Chain domain cerificate with root and issuing authority 
    - Upload chained certificate to the keystore
    - Use this keystore into your web server configuration to validate HTTPS url

mTLS
1. TLS which does client authentication as well
2. https://www.cloudflare.com/en-gb/learning/access-management/what-is-mutual-tls/

HTTP1 vs HTTP2 vs WebSockets
1. https://www.cloudflare.com/en-gb/learning/performance/http2-vs-http1.1/
2. https://stackoverflow.com/questions/28582935/does-http-2-make-websockets-obsolete

Webhook vs Websocket vs Server Side Events
1. https://stackoverflow.com/questions/23172760/differences-between-webhook-and-websocket
2. https://stackoverflow.com/questions/53342419/what-is-the-difference-between-server-side-event-and-web-hook-reverse-api

[To-do]REST vs GraphQL 

REST vs gRPC
1. https://blog.postman.com/grpc-vs-rest
2. https://blog.restcase.com/http2-benefits-for-rest-apis/
3. https://stackoverflow.com/questions/31692868/rest-api-with-http-2
