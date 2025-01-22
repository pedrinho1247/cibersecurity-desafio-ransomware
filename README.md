# Projeto Básico - Ransomware

> Projeto desenvolvido no *Santander Bootcamp Cibersegurança*  
> Realizado pela [DIO](https://web.dio.me/track/santander-bootcamp-ciberseguranca?tab=about) em parceria com o Santander Universidades.

## 🛠️ Sobre o Projeto

Este projeto é uma implementação simples de um ransomware, criado para fins educacionais como parte do Bootcamp de Cibersegurança. O objetivo é demonstrar como funciona o processo de encriptação e descriptografia de arquivos utilizando Python e a biblioteca `pyaes`.

⚠ **Aviso**: Este projeto é estritamente educacional e deve ser utilizado com responsabilidade. Nunca utilize este ou qualquer outro código malicioso em sistemas ou arquivos de terceiros sem autorização explícita.

---

## 📂 Estrutura do Projeto

O projeto é composto pelos seguintes arquivos:

- **`teste.txt`**  
  Um arquivo de exemplo que será usado como alvo para a encriptação. Ele terá seu conteúdo criptografado durante a execução do script `encrypter.py`.

- **`encrypter.py`**  
  Um script Python responsável por criptografar o arquivo `teste.txt`. Após a encriptação, o arquivo será renomeado para `teste.txt.ransomwaretroll`, com seu conteúdo inacessível sem a chave de descriptografia.

- **`decrypter.py`**  
  Um script Python para reverter a criptografia. Ele descriptografa o arquivo `teste.txt.ransomwaretroll`, restaurando o conteúdo original de `teste.txt`.

---

## 🚀 Tecnologias Utilizadas

- **Linguagem**: Python 3.  
- **Biblioteca**: [pyaes](https://pypi.org/project/pyaes/) - Para realizar operações de criptografia AES.

---
