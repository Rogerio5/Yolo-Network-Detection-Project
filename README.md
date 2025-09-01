# Yolo-Network-Detection-Project

# 🧠 YOLOv3-Custom-Detector

## 🚀 Projeto de Detecção de Objetos com YOLOv3 — Aplicação via Google Colab

![Imagem de capa do projeto](output/yolo-detections.png)

---

## 🏅 Badges

- 📦 Tamanho do repositório / Repository Size:  
  ![GitHub repo size](https://img.shields.io/repo-size/Rogerio5/YOLOv3-Custom-Detector)

- 📄 Licença do projeto / Project License:  
  ![GitHub license](https://img.shields.io/github/license/Rogerio5/YOLOv3-Custom-Detector)

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

- Criar uma base de dados personalizada com o LabelMe  
- Treinar a rede YOLOv3 com duas classes: `"avião_movimentando"` e `"pessoas_andando_e_placas"`  
- Visualizar métricas como mAP, precisão e recall  
- Testar imagens manualmente com painel interativo  
- Gerar comparações visuais lado a lado entre imagem original e detecção

**EN:**  
This project implements a full object detection pipeline using **YOLOv3**, built on **Google Colab** and the **Darknet** framework. It enables:

- Creating a custom dataset with LabelMe  
- Training YOLOv3 with two classes: `"avião_movimentando"` and `"pessoas_andando_e_placas"`  
- Visualizing metrics like mAP, precision, and recall  
- Manually testing images with an interactive panel  
- Generating side-by-side visual comparisons between original and detected images

---

## 🚧 Status / Status

- ✅ Pipeline completo implementado no Colab  
- ✅ Treinamento funcional com duas classes personalizadas  
- ✅ Métricas extraídas e visualizações geradas  
- ✅ Pronto para adaptação com novas classes e datasets

---

## ⚙️ Funcionalidades / Features

| 🧩 Funcionalidade (PT)                      | 💡 Description (EN)                          |
|--------------------------------------------|----------------------------------------------|
| 🏗 Estrutura automatizada de projeto        | 🏗 Automated project structure setup          |
| 🖼 Conversão LabelMe → YOLO                 | 🖼 LabelMe to YOLO annotation conversion      |
| 🏋️ Treinamento com transfer learning        | 🏋️ Training with transfer learning            |
| 📊 Métricas: mAP, precisão, recall          | 📊 Metrics: mAP, precision, recall            |
| 🧪 Painel interativo para inferência        | 🧪 Interactive inference panel                |
| 🖼 Comparações lado a lado                  | 🖼 Side-by-side visual comparisons            |
| 📤 Upload e visualização de imagens         | 📤 Upload and visualization of labeled images |

---

## 🚀 Execução / Execution

**PT:**  
Para executar o projeto no Colab:

1. Clone o repositório do Darknet  
2. Compile com suporte a GPU, CUDNN e OpenCV  
3. Prepare a estrutura de diretórios e arquivos `.cfg`, `.data`, `.names`  
4. Converta os rótulos do LabelMe para o formato YOLO  
5. Treine o modelo com `yolov3.conv.81`  
6. Gere métricas com `detector map`  
7. Teste imagens com painel interativo e visualize comparações

**EN:**  
To run the project on Colab:

1. Clone the Darknet repository  
2. Compile with GPU, CUDNN, and OpenCV support  
3. Prepare directory structure and config files (`.cfg`, `.data`, `.names`)  
4. Convert LabelMe annotations to YOLO format  
5. Train the model using `yolov3.conv.81`  
6. Generate metrics with `detector map`  
7. Test images with an interactive panel and view comparisons

---

## 🌐 Acesso / Access

- [Repositório GitHub / GitHub Repository](https://github.com/Rogerio5/YOLOv3-Custom-Detector)

---

## 🧰 Tecnologias / Technologies

<p>
  <img align="left" alt="Python" title="Python" width="30px" style="padding-right: 10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg"/>
  <img align="left" alt="OpenCV" title="OpenCV" width="30px" style="padding-right: 10px;" src="https://upload.wikimedia.org/wikipedia/commons/3/32/OpenCV_Logo_with_text_svg_version.svg"/>
  <img align="left" alt="Darknet" title="Darknet" width="30px" style="padding-right: 10px;" src="https://pjreddie.com/media/image/yolo.png"/>
  <img align="left" alt="LabelMe" title="LabelMe" width="30px" style="padding-right: 10px;" src="https://labelme.csail.mit.edu/Release3.0/logo.png"/>
  <img align="left" alt="Google Colab" title="Google Colab" width="30px" style="padding-right: 10px;" src="https://upload.wikimedia.org/wikipedia/commons/d/d0/Google_Colaboratory_SVG_Logo.svg"/>
</p>

<br clear="all"/>

---

## 👨‍💻 Desenvolvedor / Developer

- [Rogerio](https://github.com/Rogerio5)

---

## 📜 Licença / License

Este projeto está sob licença MIT. Para mais detalhes, veja o arquivo `LICENSE`.  
This project is under the MIT license. For more details, see the `LICENSE` file.

---

## 🏁 Conclusão / Conclusion

**PT:**  
Este projeto demonstra como aplicar YOLOv3 em um cenário real com classes personalizadas, desde a rotulagem até a inferência. A estrutura modular permite expandir para novos datasets, ajustar hiperparâmetros e integrar com outras ferramentas de análise visual.

**EN:**  
This project showcases how to apply YOLOv3 in a real-world scenario with custom classes, from labeling to inference. Its modular structure allows expansion to new datasets, hyperparameter tuning, and integration with other visual analysis tools.
