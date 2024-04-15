# Ransomware Simples
Este é um projeto simples de ransomware desenvolvido em Python, que consiste em um encriptador e um descriptador de arquivos.

## Funcionalidades

### Encriptador:

O encriptador utiliza um algoritmo de criptografia para encriptar os arquivos do sistema alvo.
Os arquivos são encriptados com uma chave pŕe determinada dentro do script, que é então encriptado.
Os arquivos encriptados recebem uma extensão personalizada para indicar que foram comprometidos.

### Descriptador:
O descriptador é responsável por decifrar os arquivos encriptados utilizando a mesma senha que foi definida na criptografia do arquivo original.
A chave de descriptografia deve ser fornecida pelo responsável do ataque.

### Requisitos
Python 3.x
Biblioteca cryptography (instalável via pip install cryptography)

### Utilização
Encriptar Arquivos:

Execute o script encryptor.py com o Comando 
Python encryptador.py

Execute o script encryptor.py com o Comando 
Python decryptador.py

# Aviso Legal
Este projeto é fornecido apenas para fins educacionais e de pesquisa. O uso deste software para qualquer finalidade maliciosa é estritamente proibido. O autor não se responsabiliza por qualquer dano causado pelo uso indevido deste software.
