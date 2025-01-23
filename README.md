
![Criando_um_Ransomware_com_Python](https://github.com/user-attachments/assets/355e596e-0888-45ca-9dbe-173aff186c2f)

> [!WARNING]
> ### Avisos Legais ⚠️
> ***"Este projeto é destinado exclusivamente para fins educativos sobre cibersegurança. O material apresentado foi cuidadosamente analisado para evitar o uso malicioso deste estudo. A utilização deste conteúdo deve estar de acordo com a lei e NÃO irei me responsabilizar por qualquer uso indevido ou ilegal das informações aqui fornecidas."***

> [!WARNING]
> ### Legal Disclaimer ⚠️
> ***"This project is meant solely for educational purposes in cybersecurity. The content has been carefully reviewed to discourage any malicious use. Please ensure that you use this information responsibly and in compliance with the law. I will NOT be held accountable for any misuse or illegal activities involving the materials provided here."***

### 🌍 Idioma / Language

| Idioma      | Language  |
|-------------|-----------|
| 🇧🇷 [Português](#introdução) | 🇺🇸 [English](#introduction) |

## Índice
1. [Introdução](#introdução)
2. [Ferramentas](#ferramentas)
3. [Mão na Massa](#mão-na-massa)
4. [Resultados](#resultados)

## Introdução
### Objetivo
Este projeto tem como objetivo criar um ransomware para criptografar arquivos utilizando a linguagem Python.

## Ferramentas
![Kali](https://img.shields.io/badge/Kali-268BEE?style=for-the-badge&logo=kalilinux&logoColor=white)

## Mão na Massa
1. Abrir o terminal do Kali Linux;
   
  ![Terminal](https://github.com/user-attachments/assets/0b10df7c-122a-4a13-8af7-8838a77aefc6)

2. Criar o arquivo de texto que será criptografado: ``nano Documento_Confidencial``;

  ![Criar documento](https://github.com/user-attachments/assets/42fce813-c2de-48a7-a6b7-8f2b13dd420c)
   
3. Adicionar algum texto ao arquivo;

  ![Preencher Documento](https://github.com/user-attachments/assets/fb9f86b4-406a-4ef0-afa1-0e0e18dd2b28)
   
4. Criar o script de criptografia: ``touch encrypter.py``;

![Criar criptografador](https://github.com/user-attachments/assets/93660654-55a9-475f-94eb-60e2b11a1485)

5. Criar o script de descriptografar: ``touch decrypter.py``;

![Criar descriptografador](https://github.com/user-attachments/assets/ff9e17fa-c300-4d4e-9ba2-198a8ea06e91)

6. Editar o código no script de criptografia: ``nano encrypter.py``;

![Editar criptografador](https://github.com/user-attachments/assets/19b5c788-127d-434a-a3cf-bf3fac62edc2)

7. Adicionar código de criptografia;

![Código do criptografador](https://github.com/user-attachments/assets/cf4f18cf-9e83-4a38-9706-0f94e5c40667)

8. Adicionar código de descriptografia;

![Código do descriptografador](https://github.com/user-attachments/assets/e824742b-d46d-4579-bc2c-fa9add5a04ff)

9. Rodar o código de criptografia e verificar resultado: ``python encrypter.py``, ``nano Documento_Confidencial.txt.ransomwaretroll``

![Roda criptografia](https://github.com/user-attachments/assets/e3a98375-5f94-4227-aed3-6f23c8c8fdc9)

10. Rodar o código de descriptografia e verificar resultado: ``python decrypter.py``, ``nano Documento_Confidencial.txt``

![Roda descriptografia](https://github.com/user-attachments/assets/8afa1ed4-97b5-41f7-9485-8f950c7cfccc)

### Resultados
#### Criptografia

![Resultado Criptografia](https://github.com/user-attachments/assets/f3a75879-d2a1-4f29-949a-2691a0a40811)

#### Descriptografia

![Resultado Descriptografia](https://github.com/user-attachments/assets/1bdc2cae-f2ff-4699-9e29-def0d6aa52b9)


---

### 🌍 Language

| Language  | Idioma      |
|-----------|-------------|
| 🇺🇸 [English](#introduction) | 🇧🇷 [Português](#introdução) |

## Table of Contents
1. [Introduction](#introduction)
2. [Tools](#tools)
3. [Hands-on](#hands-on)
4. [Results](#results)

## Introduction
### Objective
This project aims to create ransomware to encrypt files using the Python programming language.

## Tools
![Kali](https://img.shields.io/badge/Kali-268BEE?style=for-the-badge&logo=kalilinux&logoColor=white)

## Hands-on
1. Open the Kali Linux terminal:
   
  ![Terminal](https://github.com/user-attachments/assets/0b10df7c-122a-4a13-8af7-8838a77aefc6)

2. Create the text file to be encrypted: ``nano Documento_Confidencial``;

  ![Criar documento](https://github.com/user-attachments/assets/42fce813-c2de-48a7-a6b7-8f2b13dd420c)
   
3. Add some text to the file:

  ![Preencher Documento](https://github.com/user-attachments/assets/fb9f86b4-406a-4ef0-afa1-0e0e18dd2b28)
   
4. Create the encryption script: ``touch encrypter.py``;

![Criar criptografador](https://github.com/user-attachments/assets/93660654-55a9-475f-94eb-60e2b11a1485)

5. Create the decryption script: ``touch decrypter.py``;

![Criar descriptografador](https://github.com/user-attachments/assets/ff9e17fa-c300-4d4e-9ba2-198a8ea06e91)

6. Edit the encryption script code: ``nano encrypter.py``;

![Editar criptografador](https://github.com/user-attachments/assets/19b5c788-127d-434a-a3cf-bf3fac62edc2)

7. Add encryption code;

![Código do criptografador](https://github.com/user-attachments/assets/cf4f18cf-9e83-4a38-9706-0f94e5c40667)

8. Add decryption code;

![Código do descriptografador](https://github.com/user-attachments/assets/e824742b-d46d-4579-bc2c-fa9add5a04ff)

9. Run the encryption script and check the result: ``python encrypter.py``, ``nano Documento_Confidencial.txt.ransomwaretroll``

![Roda criptografia](https://github.com/user-attachments/assets/e3a98375-5f94-4227-aed3-6f23c8c8fdc9)

10. Run the decryption script and check the result: ``python decrypter.py``, ``nano Documento_Confidencial.txt``

![Roda descriptografia](https://github.com/user-attachments/assets/8afa1ed4-97b5-41f7-9485-8f950c7cfccc)

### Results
#### Encryption

![Resultado Criptografia](https://github.com/user-attachments/assets/f3a75879-d2a1-4f29-949a-2691a0a40811)

#### Decryption

![Resultado Descriptografia](https://github.com/user-attachments/assets/1bdc2cae-f2ff-4699-9e29-def0d6aa52b9)


