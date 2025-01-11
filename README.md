# 🔍 Image Similarity Recommendation System

Este repositório contém um sistema de recomendação de imagens baseado em **similaridade visual** usando redes neurais profundas para extração de features visuais. O projeto foi desenvolvido para identificar imagens similares em um conjunto de quatro categorias específicas:

- 🧸 **Ursos de Pelúcia**  
- 💄 **Pincéis de Blush**  
- 💧 **Garrafinhas de Água**  
- 💨 **Secadores de Cabelo**

O sistema utiliza o modelo **ResNet50** pré-treinado na ImageNet para extrair representações (embeddings) das imagens, e calcula a similaridade usando **distância cosseno** ou **distância euclidiana**. O código é totalmente genérico e pode ser adaptado para diferentes categorias de imagens.

---

## 📂 Estrutura do Projeto

```bash
📦 image_similarity_recommendation
 ┣ 📂 images               # Diretório com as imagens
 ┣ 📜 main.py              # Código principal do sistema de recomendação
 ┗ 📜 README.md            # Descrição do projeto
```

---

## 🚀 Como Funciona

1. O sistema carrega um conjunto de imagens de diferentes categorias.
2. A imagem de entrada é processada e suas features são extraídas usando o modelo ResNet50.
3. Para cada imagem no conjunto, o sistema calcula a similaridade visual em relação à imagem de entrada.
4. As imagens mais similares são exibidas em uma interface gráfica, com a imagem de entrada primeiro e as recomendações em sequência.

---

## 🛠️ Requisitos

- Python 3.7+
- TensorFlow/Keras
- NumPy
- SciPy
- Matplotlib

---

## 📸 Exemplo de Uso

1. Insira suas imagens no diretório especificado.
2. Modifique o caminho da imagem de entrada no código.
3. Execute o script para visualizar as recomendações.

```bash
python main.py
```

---

## 📊 Resultados

O sistema exibe as imagens recomendadas em uma janela gráfica, destacando a **imagem de entrada** e as **imagens mais similares** encontradas no conjunto.

![Exemplo de Resultado](example_output.png)

---

## 🧪 Personalização

Para usar o sistema com outras categorias, basta substituir as imagens no diretório e ajustar o código, se necessário. Não há necessidade de mudar o algoritmo de recomendação.

Exemplo de categorias que você pode usar:

- 🍩 Doces
- 🕶️ Acessórios
- 📚 Livros
- 🏀 Equipamentos esportivos

---

## 📂 Dataset Exemplo
Um dataset simples pode ser estruturado da seguinte forma:

```bash
📂 dataset
 ┣ 📂 teddy_bears
 ┃ ┣ 🧸 teddy1.jpg
 ┃ ┗ 🧸 teddy2.jpg
 ┣ 📂 blush_brushes
 ┃ ┣ 💄 blush1.jpg
 ┃ ┗ 💄 blush2.jpg
 ┣ 📂 water_bottles
 ┃ ┣ 💧 bottle1.jpg
 ┃ ┗ 💧 bottle2.jpg
 ┗ 📂 hair_dryers
   ┣ 💨 dryer1.jpg
   ┗ 💨 dryer2.jpg
```

---

## 📬 Contato
Se tiver dúvidas ou sugestões, fique à vontade para entrar em contato!

**Desenvolvido por [Seu Nome]** 💻


