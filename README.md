# RSA-Algorithm (Rivest-Shamir-Adleman)

RSA algorithm is an asymmetric cryptography algorithm. <br>Asymmetric actually means that it works on two different keys i.e. Public Key and Private Key.<br> As the name describes that the Public Key is given to everyone and the Private key is kept private.<br><br>

**An example of asymmetric cryptography: <br>**

A client (for example browser) sends its public key to the server and requests some data.<br>
The server encrypts the data using the client’s public key and sends the encrypted data.<br>
The client receives this data and decrypts it.<br>
Since this is asymmetric, nobody else except the browser can decrypt the data even if a third party has the public key of the browser.<br><br>

**The idea!<br>**
The idea of RSA is based on the fact that it is difficult to factorize a large integer.<br> The public key consists of two numbers where one number is a multiplication of two large prime numbers.<br> And private key is also derived from the same two prime numbers.<br> So if somebody can factorize the large number, the private key is compromised.<br> Therefore encryption strength totally lies on the key size and if we double or triple the key size, the strength of encryption increases exponentially.<br> RSA keys can be typically 1024 or 2048 bits long, but experts believe that 1024-bit keys could be broken in the near future.<br> But till now it seems to be an infeasible task.<br><br>

**Where are RSA algorithms used?**<br>
 People hoping to send secure messages, gain access to secure websites, or prove the authenticity of messages might use RSA.
 
 
 
 ![alice](https://github.com/bensonjose/RSA-Algorithm-Explained/assets/90842204/dfefd2b8-dfb5-48fc-8304-0199cfa791e7)

**Fig: Working of RSA Algorithm**
