# 🧠 Projeto - Classificação com CNN no FashionMNIST (DataCamp)

Este repositório contém a implementação de um projeto-atividade desenvolvido na plataforma [DataCamp](https://www.datacamp.com/), com foco em redes neurais convolucionais (CNNs) aplicadas à tarefa de **classificação de imagens** utilizando o dataset **FashionMNIST**.

## 📂 Conteúdo do Projeto

- Redimensionamento de imagens de para `64x64` para treinar uma CNN.
- Construção de uma arquitetura CNN com `PyTorch`, utilizando camadas:
  - `Conv2d`, `ELU`, `MaxPool2d` e `Linear`
- Loop de treinamento completo com:
  - Otimizador (`ADAM`), função de perda (`CrossEntropyLoss`), forward e backward pass.
- Uso do `DataLoader` com tratamento de `batch_size` e `shuffle`.

## 🛠️ Tecnologias Utilizadas

- Python
- PyTorch
- torchvision.datasets.FashionMNIST

## 📌 Observações

- O treinamento foi realizado com `batch_size=64`, o que resultou em aproximadamente 940 iterações por época e um tempo de execução relativamente rápido, já que utilize CPU.

---

Sinta-se à vontade para clonar, modificar e explorar este projeto como ponto de partida para experimentos com redes neurais convolucionais no PyTorch!
