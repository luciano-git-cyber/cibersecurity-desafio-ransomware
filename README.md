## 🔒 Projeto Prático: Criando um Ransomware em Python
Este projeto é uma simulação de um ransomware criado em Python com o objetivo de criptografar e descriptografar arquivos com o algoritmo AES (Advanced Encryption Standard).


## 📌 Funcionamento:
O script encrypter.py criptografa o arquivo teste.txt, o exclui e cria um novo arquivo criptografado teste.txt.ransomwaretroll.
O script decrypter.py descriptografa esse arquivo, restaurando ao conteúdo original.

## 🚀 Ferramentas Utilizadas
Python 3 no Kali Linux

## 📥 Passo a passo:
🔹 1. usar como o referência os scripts do repositório:
 https://github.com/cassiano-dio/cibersecurity-desafio-ransomware
 

🔹 2. Instalar dependências:
Caso não tenha a biblioteca pyaes, instale com:
sudo apt install python3-pyaes

🔹 3. Criptografar o arquivo executando:
python encrypter.py
esse comando irá remover o arquivo teste.txt e criará o teste.txt.ransomwaretroll. criptografado.

🔹 4. Descriptografar o arquivo executando:
python decrypter.py
Esse comando restaurará o arquivo teste.txt com a mensagem descriptografada.
