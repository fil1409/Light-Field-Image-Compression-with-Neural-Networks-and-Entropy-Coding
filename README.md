# Compressione di Immagini Light Field con Codifica Entropica e Deep Learning

Questo progetto esplora l'applicazione di tecniche di deep learning e codifica entropica per la compressione di immagini Light Field (LFI). Sono stati sperimentati diversi scenari variando il numero di immagini, la risoluzione e il numero di epoche di addestramento.

## Dataset

Il dataset utilizzato è il **RGB Light Field Dataset**, disponibile su Kaggle:
👉 [https://www.kaggle.com/datasets/julesh7/rgb-light-field-dataset]

## Contenuto

- 📂 `200 epoche e 200 immagini`: compressione con 200 immagini e 200 epoche.
- 📂 `200 epoche e 200 immagini_512x512`: stessa configurazione con risoluzione 512x512.
- 📂 `200 epoche e 500 immagini_512x512`: dataset esteso.
- 📂 `500 epoche e 200 immagini`: maggiore profondità di addestramento.

Ogni cartella contiene i notebook Jupyter che mostrano:

- Addestramento di una rete neurale per la compressione
- Applicazione di codifica entropica
- Testing e valutazione con metriche quantitative

## Tecnologie Utilizzate

- Python
- TensorFlow / Keras (o simili)
- Jupyter Notebook
- Tecniche di codifica entropica

## Come Iniziare

1. Clona la repository:
   git clone https://github.com/tuo-utente/nome-repository.git
2. Apri i file .ipynb con Jupyter.

# Light Field Image Compression with Entropy Coding and Deep Learning

This project explores the use of deep learning and entropy coding techniques for compressing Light Field Images (LFI). Various experiments were conducted by changing the number of images, resolution, and training epochs.

## Dataset

The dataset used is the **RGB Light Field Dataset**, available on Kaggle:
👉 [https://www.kaggle.com/datasets/julesh7/rgb-light-field-dataset]

## Content

- 📂 `200 epochs and 200 images`: compression using 200 images and 200 training epochs.
- 📂 `200 epochs and 200 images_512x512`: same setting with 512x512 resolution.
- 📂 `200 epochs and 500 images_512x512`: extended dataset.
- 📂 `500 epochs and 200 images`: deeper training configuration.

Each folder contains Jupyter notebooks showing:

- Neural network training for image compression
- Application of entropy coding
- Testing and performance evaluation

## Technologies Used

- Python
- TensorFlow / Keras (or equivalent)
- Jupyter Notebook
- Entropy coding techniques

## Getting Started

1. Clone the repository:
   git clone https://github.com/your-username/your-repository-name.git
2. Open .ipynb files with Jupyter.
