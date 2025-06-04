# 🕵️‍♂️ webrecon.sh

Script simples em Bash para realizar **força bruta de diretórios ou arquivos** em aplicações web, utilizando uma wordlist personalizada. Ideal para fases iniciais de reconhecimento em testes de penetração (pentest).

---

## 📂 Descrição

Este script utiliza `curl` para testar a existência de caminhos específicos em um alvo HTTP/HTTPS com base em uma lista de palavras (wordlist). Ele verifica se a resposta retorna **HTTP 200 OK**, indicando que o diretório ou arquivo existe.

---

## 🛠️ Requisitos

- `bash`
- `curl`
- Wordlist chamada `lista2.txt` no mesmo diretório do script

---

## ▶️ Uso

```bash
chmod +x webrecon.sh
./webrecon.sh <URL-alvo> <extensao>

