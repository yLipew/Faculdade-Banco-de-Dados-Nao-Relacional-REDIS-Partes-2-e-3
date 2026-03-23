# 🚀 Laboratório de Estruturas de Dados e Performance em Redis

![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green)

---

Este repositório contém um laboratório prático em Python desenvolvido para explorar o potencial do **Redis** como uma solução de armazenamento de dados em memória de ultra-performance. O projeto demonstra como o Redis lida com grandes volumes de dados, diferentes estruturas e latência mínima.

---

## 📌 Índice

- 📖 Sobre o Projeto  
- ⚙️ Funcionalidades e Testes  
- 🗂️ Estruturas de Dados Exploradas  
- 🛠️ Pré-requisitos  
- 📚 Objetivo Acadêmico  

---

## 📖 Sobre o Projeto

O script desenvolvido realiza uma bateria de testes automatizados para validar os quatro pilares do Redis:

- **Performance:** Velocidade de leitura e escrita instantânea  
- **Escalabilidade:** Capacidade de gerenciar milhões de chaves  
- **Flexibilidade:** Uso de tipos de dados complexos  
- **Baixa Latência:** Eficiência como camada de cache  

---

## ⚙️ Funcionalidades e Testes

### 🏎️ Alto Desempenho
O código mensura o tempo de operações `SET` e `GET`, que geralmente ocorrem em frações de milissegundos.

### 📈 Escalabilidade (Stress Test)
Executa um loop de **1.000.000 de inserções** para validar a robustez do Redis sob alta carga.

### ⚡ Baixa Latência (Cache)
Simula acessos repetitivos a dados, demonstrando latência extremamente baixa em consultas subsequentes.

---

## 🗂️ Estruturas de Dados Exploradas

- **Strings:** Armazenamento de mensagens simples  
- **Lists:** Implementação de filas/pilhas (`RPUSH`)  
- **Hashes:** Estrutura de objetos (ex: usuários)  
- **Binary/Base64:** Simulação de armazenamento de imagens codificadas  

---

## 🛠️ Pré-requisitos

Antes de começar, você precisará ter instalado:

- Python 3.x  
- Redis Server ou Docker  

---

## 📚 Objetivo Acadêmico

O propósito desta atividade é consolidar o aprendizado sobre **Bancos de Dados NoSQL do tipo Chave-Valor**, abordando:

- **Performance:** Comparação com bancos relacionais  
- **Estruturas NoSQL:** Uso de listas, hashes e strings  
- **Escalabilidade:** Testes com grande volume de dados  
- **Dados Complexos:** Uso de Base64 para arquivos binários  

---

## 👨‍💻 Autor

**Felipe Mendonça**  
Inteligência Artificial / Banco de Dados Não Relacional  
FATESG / SENAI  
2026
