# Mesclador de PDFs 📃✅

Este projeto é um simples script em Python que mescla vários arquivos PDF em um único arquivo PDF. Se você tem vários PDFs e deseja combiná-los em um só, este script é para você!

## O Que Este Script Faz

1. **Lista os Arquivos PDF:** O script procura todos os arquivos PDF no diretório chamado `arquivos`, organiza-os em ordem alfabética e mostra essa lista para você.
2. **Mescla os PDFs:** Adiciona cada PDF encontrado à uma "coleção" e, em seguida, combina tudo em um único arquivo PDF.
3. **Cria um PDF Final:** O resultado final é um novo arquivo chamado `PDF Final.pdf` que contém todos os PDFs mesclados.

## Como Usar

1. **Prepare os Arquivos PDF:**
   - Coloque todos os arquivos PDF que você deseja mesclar dentro da pasta chamada `arquivos`.

2. **Instale o PyPDF2:**
   - Primeiro, você precisa instalar a biblioteca necessária. Abra o terminal ou prompt de comando e execute:

     ```bash
     pip install pypdf2
     ```

3. **Execute o Script:**
   - Depois de instalar o `PyPDF2`, execute o script Python para mesclar seus PDFs:

     ```bash
     python seu_script.py
     ```

4. **Veja o Resultado:**
   - O script criará um arquivo chamado `PDF Final.pdf` com todos os PDFs mesclados. Você encontrará este arquivo no mesmo diretório onde o script foi executado.

## Entendendo o Código

Aqui está uma breve explicação do que o script faz:

- **Importa Bibliotecas:**
  ```python
  import PyPDF2
  import os
