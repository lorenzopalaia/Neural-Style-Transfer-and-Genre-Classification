# Neural Style Transfer & Genre Classification
Progetto per il Laboratorio di Intelligenza Artificiale, Ingegneria Informatica e Automatica, Università La Sapienza 
## Descrizione
Il progetto propone come obiettivo quello di realizzare un classificatore di generi musicali e in aggiunta un trasferimento di stile neurale tra due tracce audio sfruttando gli spettrogrammi. Per la classificazione sono stati utilizzati due approcci differenti, uno basato su Image Augumentation ed un altro che sfrutta le features delle tracce audio contenute in un file `.csv`. Per il primo approccio è stato utilizzato PyTorch mentre sono presenti un'implementazione in PyTorch ed una in Tensorflow per la classificazione attraverso features. Allo stesso modo, per il trasferimento di stile neurale sono presenti delle implementazioni in entrambi i framework
## Datasets
### Neural Style Transfer
Scaricare e decomprimere `inputs.zip`
### Genre Classification
Utilizziamo il dataset GTZAN scaricabile [qui](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification)
## Esecuzione
L'intero progetto è strutturato per essere eseguito tramite Google Colab con i dataset caricati su Google Drive. In particolare è necessario scaricare i dataset e strutturare le cartelle di Google Drive come segue inserendo la cartella Colab Notebooks nella home di Google Drive:
```
Colab Notebooks/
├── data/
│   ├── inputs/
│   │   └── inputs.zip (decompresso)
│   ├── pt_outputs/
│   └── tf_outputs/
├── GTZAN Dataset/ (decompresso)
├── models/
│   ├── pt/
│   │   ├── GC_csv/
│   │   └── GC_imgaug/
│   └── tf/
│       └── GC_csv/
└── notebooks/
    ├── GC_csv_pt_tf.ipynb
    ├── GC_imgaug_pt.ipynb
    ├── NST_pt.ipynb
    └── NST_tf.ipynb
```
Eseguire un notebook dalla cartella notebooks e utilizzare, quando possibile, il runtime GPU fornito da Colab.
