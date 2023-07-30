TLS (Transport Layer Security) is a cryptographic protocol that provides secure communication over a computer network.

TLS uses encryption algorithms to scramble the data being transmitted, making it unreadable to anyone who intercepts it without the proper decryption key.

TLS guarantees that data is not altered or corrupted during transmission. It uses message authentication codes (MACs) to verify that the data received at the other end is the same as what was sent.

TLS operates in the application layer of the OSI model and sits on top of the transport layer (e.g., TCP or UDP).

*Handshake*

he TLS protocol establishes a secure connection through a process called the "handshake." During the handshake, the client and server negotiate the encryption algorithms and other parameters to be used in the secure communication session.

The TLS (Transport Layer Security) handshake is a process that occurs when a client (like a web browser) initiates a secure connection with a server (like a website). It establishes the parameters of the secure communication session, such as encryption algorithms and cryptographic keys, before any actual data is exchanged.

Here's a simplified overview of the TLS handshake process:

1. Server presents the certificate: The server sends its TLS certificate to the client during the TLS handshake process. The certificate contains the server's public key, its domain name (or IP address), and other relevant information.
    
2. Client verifies the certificate: The client checks the validity of the certificate to ensure that it has not expired, is issued by a trusted Certificate Authority (CA), and matches the domain name of the server. If any of these checks fail, the client will display a warning to the user, indicating that the connection may not be secure.
    
3. Key exchange: If the client trusts the certificate, it proceeds with the TLS handshake, during which the client and server exchange cryptographic keys and agree on encryption algorithms to use for secure communication.
    
4. Secure data exchange: Once the handshake is completed, the client and server can securely exchange data over the encrypted connection, ensuring confidentiality and integrity during transmission.

The TLS handshake ensures that the client and server can establish a secure and private channel for communication, protecting sensitive data from eavesdropping and tampering. After the handshake is completed, the TLS session remains active, and the client and server can continue exchanging data securely until the session is terminated.

TLS Certificate




1.3 is the latest version

Apart from [[https]] TLS is used in email communications, VPN, VoIp, IOT devices etc