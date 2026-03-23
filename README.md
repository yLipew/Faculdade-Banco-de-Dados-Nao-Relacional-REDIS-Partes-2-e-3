# 🚀 Laboratório de Estruturas de Dados e Performance em Redis

![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)
![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow?style=for-the-badge)

Este repositório contém um laboratório prático em **Python** desenvolvido para explorar o potencial do **Redis** como uma solução de armazenamento de dados em memória de ultra-performance. O projeto demonstra como o Redis lida com grandes volumes de dados, diferentes estruturas e latência mínima.

## 📌 Índice
- [Sobre o Projeto](#-sobre-o-projeto)
- [Funcionalidades e Testes](#-funcionalidades-e-testes)
- [Estruturas de Dados Exploradas](#-estruturas-de-dados-exploradas)
- [Pré-requisitos](#-pré-requisitos)
- [Como Executar](#-como-executar)
- [Análise Técnica](#-análise-técnica)

---

## 📖 Sobre o Projeto

O script desenvolvido realiza uma bateria de testes automatizados para validar os quatro pilares do Redis:
1. **Performance**: Velocidade de leitura e escrita instantânea.
2. **Escalabilidade**: Capacidade de gerenciar milhões de chaves sem degradação linear de performance.
3. **Flexibilidade**: Uso de tipos de dados complexos além de simples strings.
4. **Baixa Latência**: Eficiência no uso como camada de cache.

## ⚙️ Funcionalidades e Testes

### 🏎️ Alto Desempenho
O código mensura o tempo exato de uma operação de `SET` e `GET`. Em ambientes locais, essa operação costuma levar frações de milissegundos.

### 📈 Escalabilidade (Stress Test)
Executa um loop de **1.000.000 de inserções** simultâneas para demonstrar a robustez do Redis sob alta carga de escrita.

### ⚡ Baixa Latência (Cache)
Simula o acesso repetitivo a uma configuração de sistema, provando que buscas subsequentes no Redis mantêm uma latência desprezível.

## 🗂️ Estruturas de Dados Exploradas

O projeto demonstra a versatilidade do Redis através das seguintes implementações:

* **Strings**: Armazenamento de mensagens e comandos simples.
* **Lists**: Implementação de filas/pilhas usando `RPUSH`.
* **Hashes**: Armazenamento de objetos estruturados (ideal para perfis de usuário).
* **Binary/Base64**: Codificação de arquivos binários (simulado com a chave `Skyline`) para armazenamento seguro de imagens em formato texto.

---

## 🛠️ Pré-requisitos

Antes de começar, você precisará ter instalado:
* [Python 3.x](https://www.python.org/)
* [Redis Server](https://redis.io/downloads/) ou [Docker](https://www.docker.com/)

## 🚀 Como Executar

1. **Clone o repositório**:
   ```bash
   git clone [https://github.com/yLipew/Faculdade-Banco-de-Dados-Nao-Relacional-Atividade.git](https://github.com/yLipew/Faculdade-Banco-de-Dados-Nao-Relacional-Atividade.git)
    cd Faculdade-Banco-de-Dados-Nao-Relacional-Atividade
   ```

2. **Configurar o Ambientee**:
   ```bash
    Caso use Docker:
    docker run --name redis-lab -p 6379:6379 -d redis
   ```
   
 3. **Instale a biblioteca cliente**:
   ```bash
   pip install redis
   ```

 4. **Execute**:
   ```bash
  python code.py
   ```

---

## 📚 Objetivo Acadêmico

O propósito desta atividade é consolidar o aprendizado sobre os conceitos de **Bancos de Dados NoSQL do tipo Chave-Valor**, focando nos seguintes pontos:
* **Entendimento de Performance**: Analisar a velocidade superior de bancos em memória em comparação a bancos relacionais tradicionais.
* **Manipulação de Estruturas NoSQL**: Praticar a implementação de listas, hashes e strings em um ambiente não relacional.
* **Escalabilidade Vertical**: Observar o comportamento do sistema ao lidar com grandes volumes de dados (stress test de 1 milhão de registros).
* **Tratamento de Dados Complexos**: Aplicar técnicas de serialização (Base64) para armazenar arquivos binários (imagens) dentro de estruturas de texto.

---
## 🎓 Objetivo Acadêmico

Esta atividade tem como finalidade desenvolver competências fundamentais na manipulação e análise de dados utilizando a biblioteca **Pandas** em Python.

Ao longo dos exercícios, são trabalhados conceitos essenciais como:

- Criação e estruturação de **DataFrames**
- Transformação de dados a partir de listas, dicionários e Series
- Manipulação de colunas (adição, remoção e cálculos)
- Tratamento de dados ausentes (**NaN**)
- Seleção e filtragem de dados com `loc` e `iloc`
- Uso de slicing para extração de subconjuntos
- Integração e concatenação de múltiplos conjuntos de dados
- Exploração de atributos e métodos nativos do Pandas

O objetivo é proporcionar uma base sólida para aplicações futuras em:
- **Análise de Dados**
- **Business Intelligence (BI)**
- **Ciência de Dados**
- **Engenharia de Dados**

Esta prática contribui diretamente para o desenvolvimento do raciocínio lógico aplicado à manipulação de dados e prepara o aluno para cenários reais do mercado de tecnologia.

---
## 👨‍💻 Autor

**Felipe Mendonça** Inteligência Artificial / Business Inteligencee  
**FATESG / SENAI**   
2026
   
     
