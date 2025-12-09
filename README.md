# 🚗 Smart Gate AI - Reconhecimento de Placas Veiculares (LPR)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green)
![EasyOCR](https://img.shields.io/badge/AI-EasyOCR-yellow)
![Status](https://img.shields.io/badge/Status-Prototype-orange)

## 📋 Sobre o Projeto

Este projeto é uma **Prova de Conceito (PoC)** de um sistema de controle de acesso residencial baseado em Inteligência Artificial. Utilizando técnicas de **OCR (Optical Character Recognition)**, o sistema é capaz de identificar placas de veículos em imagens e validar a entrada com base em uma lista de moradores autorizados.

O objetivo é simular a lógica de um portão eletrônico inteligente que elimina a necessidade de controles remotos físicos.

## 🚀 Funcionalidades

* **Leitura de Placas:** Identifica caracteres alfanuméricos em placas (Padrão Mercosul e Antigo).
* **Validação de Acesso:** Compara a placa lida com um "banco de dados" (lista) de usuários permitidos.
* **Feedback Visual:** Desenha uma *bounding box* (caixa verde) ao redor da placa identificada na imagem.
* **Log de Decisão:** Informa no console se o acesso foi `PERMITIDO` ou `NEGADO` e simula o envio de sinal para o motor.

## 🛠️ Tecnologias Utilizadas

* **Python:** Linguagem principal.
* **EasyOCR:** Biblioteca de Deep Learning para extração de texto (suporta GPU e CPU).
* **OpenCV:** Processamento de imagem (pré-processamento e desenho na tela).
* **Matplotlib:** Visualização dos resultados.

## 📦 Como Executar

### Pré-requisitos
Certifique-se de ter o Python instalado. Recomenda-se o uso de um ambiente virtual (`venv`) ou Google Colab.
