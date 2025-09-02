# Yolo-Network-Detection-Project

# 🧠 Projeto YOLOv3 — Capacete & Colete Detector

## 🚀 Detecção de EPIs com YOLOv3 via Google Colab

![Imagem de capa do projeto](imagens_rotuladas/exemplo-deteccao.png)

---

## 🏅 Badges

- 📦 Tamanho do repositório / Repository Size:  
  ![GitHub repo size](https://img.shields.io/repo-size/Rogerio5/YOLOv3-EPI-Detector)

- 📄 Licença do projeto / Project License:  
  ![GitHub license](https://img.shields.io/github/license/Rogerio5/YOLOv3-EPI-Detector)

---

## 📋 Índice / Table of Contents

- [Descrição / Description](#descrição--description)  
- [Status / Status](#status--status)  
- [Funcionalidades / Features](#funcionalidades--features)  
- [Execução / Execution](#execução--execution)  
- [Tecnologias / Technologies](#tecnologias--technologies)  
- [Desenvolvedor / Developer](#desenvolvedor--developer)  
- [Licença / License](#licença--license)  
- [Conclusão / Conclusion](#conclusão--conclusion)  

---

## 📖 Descrição / Description

**PT:**  
Este projeto implementa um pipeline completo de detecção de objetos com **YOLOv3**, utilizando o **Google Colab** e o framework **Darknet**. A aplicação permite:

- Baixar imagens rotuladas automaticamente com OIDv4 Toolkit  
- Treinar a rede YOLOv3 com duas classes: `"capacete"` e `"colete"`  
- Visualizar métricas como mAP, precisão e recall  
- Testar imagens manualmente com painel interativo  
- Gerar comparações visuais lado a lado entre imagem original e detecção  
- Validar a qualidade do dataset com bounding boxes desenhadas

**EN:**  
This project implements a full object detection pipeline using **YOLOv3**, built on **Google Colab** and the **Darknet** framework. It enables:

- Downloading auto-labeled images via OIDv4 Toolkit  
- Training YOLOv3 with two classes: `"helmet"` and `"safety_vest"`  
- Visualizing metrics like mAP, precision, and recall  
- Manually testing images with an interactive panel  
- Generating side-by-side visual comparisons between original and detected images  
- Validating dataset quality with bounding boxes

---

## 🚧 Status / Status

- ✅ Pipeline completo implementado no Colab  
- ✅ Treinamento funcional com duas classes personalizadas  
- ✅ Métricas extraídas e visualizações geradas  
- ✅ Relatório de qualidade do dataset incluído  
- ✅ Pronto para adaptação com novas classes e datasets

---

## ⚙️ Funcionalidades / Features

| 🧩 Funcionalidade (PT)                      | 💡 Description (EN)                          |
|--------------------------------------------|----------------------------------------------|
| 📦 Download automático com OIDv4 Toolkit    | 📦 Auto-labeled image download via OIDv4     |
| 🖼 Conversão para formato YOLO               | 🖼 Annotation conversion to YOLO format       |
| 🏋️ Treinamento com transfer learning        | 🏋️ Training with transfer learning            |
| 📊 Métricas: mAP, precisão, recall          | 📊 Metrics: mAP, precision, recall            |
| 🧪 Painel interativo para inferência        | 🧪 Interactive inference panel                |
| 🖼 Comparações lado a lado                  | 🖼 Side-by-side visual comparisons            |
| 📋 Relatório de qualidade do dataset        | 📋 Dataset quality report with bounding boxes |

---

## 🚀 Execução / Execution

**PT:**  
Para executar o projeto no Colab:

1. Clone o repositório do Darknet  
2. Compile com suporte a GPU, CUDNN e OpenCV  
3. Baixe imagens com OIDv4 Toolkit  
4. Converta os rótulos para o formato YOLO  
5. Prepare os arquivos `.cfg`, `.data`, `.names`  
6. Treine o modelo com `darknet53.conv.74`  
7. Gere métricas com `-map` ativado  
8. Teste imagens com painel interativo  
9. Valide o dataset com bounding boxes desenhadas

**EN:**  
To run the project on Colab:

1. Clone the Darknet repository  
2. Compile with GPU, CUDNN, and OpenCV support  
3. Download images using OIDv4 Toolkit  
4. Convert annotations to YOLO format  
5. Prepare `.cfg`, `.data`, `.names` files  
6. Train the model using `darknet53.conv.74`  
7. Generate metrics with `-map` enabled  
8. Test images with an interactive panel  
9. Validate dataset with bounding boxes

---

## 🌐 Acesso / Access

- [Repositório GitHub / GitHub Repository](https://github.com/Rogerio5/YOLOv3-EPI-Detector)

---

## 🧰 Tecnologias / Technologies

<p>
  <img align="left" alt="Python" title="Python" width="30px" style="padding-right: 10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg"/>
  <img align="left" alt="OpenCV" title="OpenCV" width="30px" style="padding-right: 10px;" src="https://upload.wikimedia.org/wikipedia/commons/3/32/OpenCV_Logo_with_text_svg_version.svg"/>
  <img align="left" alt="Darknet" title="Darknet" width="30px" style="padding-right: 10px;" src="https://darknetcv.ai/darknet_logo_blue.png"/>
  <img align="left" alt="Google Colab" title="Google Colab" width="30px" style="padding-right: 10px;" src="https://upload.wikimedia.org/wikipedia/commons/d/d0/Google_Colaboratory_SVG_Logo.svg"/>
</p>

<br clear="all"/>

---

## 👨‍💻 Desenvolvedor / Developer

- [Rogerio](https://github.com/Rogerio5)  
📍 Agudos, São Paulo, Brasil  
🗓️ Setembro de 2025

---

## 📜 Licença / License

Este projeto está sob licença MIT. Para mais detalhes, veja o arquivo `LICENSE`.  
This project is under the MIT license. For more details, see the `LICENSE` file.

---

## 🏁 Conclusão / Conclusion

**PT:**  
Este projeto demonstra como aplicar YOLOv3 em um cenário real com classes personalizadas, desde a coleta de dados até a inferência e validação. A estrutura modular permite expandir para novos datasets, ajustar hiperparâmetros e integrar com outras ferramentas de análise visual.

**EN:**  
This project showcases how to apply YOLOv3 in a real-world scenario with custom classes, from data collection to inference and validation. Its modular structure allows expansion to new datasets, hyperparameter tuning, and integration with other visual analysis tools.
