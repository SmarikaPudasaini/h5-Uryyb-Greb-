# h5-Uryyb-Greb-

Summary of CRYPTOGRAPHY -: It is a science of securing communation and information using mathematical techniques focused on how algorithms, protocals and syatem are implemented to secure data. Email security, Digital payments, Authentication, Data storage, Blockchain and webs, secure commucations are the area where cryptographics are used which seems to be everyday life uses. Furthermore it makes the internet, banking, communations and digital life safe and trustworthy. 

## SEND ENCRYPTED AND SIGNED MESSAGE-gpg

Firstly, I generate my key pair using $ gpg --gen-key , give my name and email as shown in the example

Then export my public keys using my email and signature. 

Again Imported receint´s public key by using  imports the key $ gpg --import alice.pub in this way we share public keys establishing trust over untrusted channel.

After this i write a secret message  $ micro message.txt and saves it

Again, encrypts and signs the message using $ gpg --homedir . --encrypt --recipient jaduu@example.com.invalid --sign --output encrypted.pgp --armor message.txt

Finally, message is decrypted using secret key which is signature in this case.
