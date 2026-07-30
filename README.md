# 🍌 Food Screening using YOLOv10

Sistema baseado em Inteligência Artificial para classificação automática de alimentos próprios e impróprios para consumo humano utilizando YOLOv10 e Visão Computacional.

---

## Sobre

Este projeto implementa uma solução de Visão Computacional capaz de identificar automaticamente frutas e legumes próprios e impróprios para consumo humano.

O objetivo é reduzir o tempo gasto na triagem manual, diminuindo o desperdício de alimentos e apoiando projetos sociais de distribuição de alimentos.

O modelo foi desenvolvido utilizando a técnica de Transfer Learning aplicada ao YOLOv10.

---

## Principais características

- Detecção em tempo real
- YOLOv10
- Transfer Learning
- Dataset próprio
- Bounding Boxes coloridas
- Classificação automática

---

## Classes

O modelo identifica:

- 🍌 Fresh Banana
- 🍌 Rotten Banana
- 🥭 Fresh Mamao
- 🥭 Rotten Mamao
- 🍅 Fresh Tomate
- 🍅 Rotten Tomate

---

## Dataset

Dataset utilizado.

Total:

- 2.886 imagens
- 6 classes
- divisão 80/10/10

Fontes:

- Kaggle
- Google Images
- Roboflow
- Flickr
- Yandex Images

---

## Modelo

YOLOv10n

Treinamento:

- Transfer Learning
- 30 épocas
- Batch 32
- Entrada 640x640

---

## Resultados

| Métrica | Resultado |
|---------|-----------|
| Precisão Geral | 90% |
| mAP@50 | 92,8% |
| mAP50-95 | 80,6% |

---

## Tecnologias

- Python
- OpenCV
- Ultralytics
- PyTorch
- Google Colab

---

## Estrutura

```
dataset/
    images/
    labels/

runs/

weights/

best.pt

train.py

predict.py
```

---

## Funcionamento

Entrada

Aquisição de frame de vídeo → Modelo treinado → Classificação → Bounding Box → Resultado

---

## Aplicações

- Projetos sociais de triagem de alimentos
- Centrais de distribuição
- Cooperativas
- Supermercados
- Agricultura


