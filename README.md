[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<div id="top"></div>

<br />
<div align="center">
  <a href="https://github.com/lorenzopalaia/Neural-Style-Transfer-and-Genre-Classification">
    <img src="https://colab.research.google.com/img/colab_favicon_256px.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Neural Style Transfer & Genre Classification</h3>

  <p align="center">
    The project aims to create a classifier of musical genres and to perform a neural style transfer between two audio tracks using spectrograms
    <br />
  </p>
</div>



<!-- ABOUT THE PROJECT -->
## About The Project

Project was developed for "Laboratorio di Intelligenza Artificiale" class, Ingegneria Informatica e Automatica, Università La Sapienza

Two different approaches were used for the classification, one based on Image Augumentation technique and another that uses the features of the audio tracks contained in a .csv file. For the first approach PyTorch was used while there is an implementation in PyTorch and one in Tensorflow for the classification through features. Similarly, there are implementations in both frameworks for neural style transfer

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [Colab](https://colab.research.google.com/)
* [PyTorch](https://pytorch.org/)
* [Tensorflow](https://www.tensorflow.org/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Datasets

#### Neural Style Transfer

Download and unzip `inputs.zip`

#### Genre Classification

We use the GTZAN dataset which can be downloaded [here](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification)

### Installation

The whole project is structured to be run through Google Colab with the datasets uploaded to Google Drive. In particular, it is necessary to download the datasets and structure the Google Drive folders as follows by inserting the `Colab Notebooks` folder in the Google Drive home:

```
Colab Notebooks/
├── data/
│   ├── inputs/
│   │   └── inputs.zip (unzipped)
│   ├── pt_outputs/
│   └── tf_outputs/
├── GTZAN Dataset/ (unzipped)
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

Run a notebook from the `notebooks` folder and use the GPU runtime provided by Colab whenever possible
<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Lorenzo Palaia - lorenzopalaia53@gmail.com

Project Link: [https://github.com/lorenzopalaia/Neural-Style-Transfer-and-Genre-Classification](https://github.com/lorenzopalaia/Neural-Style-Transfer-and-Genre-Classification)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/lorenzopalaia/Neural-Style-Transfer-and-Genre-Classification.svg?style=for-the-badge
[contributors-url]: https://github.com/lorenzopalaia/Neural-Style-Transfer-and-Genre-Classification/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/lorenzopalaia/Neural-Style-Transfer-and-Genre-Classification.svg?style=for-the-badge
[forks-url]: https://github.com/lorenzopalaia/Neural-Style-Transfer-and-Genre-Classification/network/members
[stars-shield]: https://img.shields.io/github/stars/lorenzopalaia/Neural-Style-Transfer-and-Genre-Classification.svg?style=for-the-badge
[stars-url]: https://github.com/lorenzopalaia/Neural-Style-Transfer-and-Genre-Classification/stargazers
[issues-shield]: https://img.shields.io/github/issues/lorenzopalaia/Neural-Style-Transfer-and-Genre-Classification.svg?style=for-the-badge
[issues-url]: https://github.com/lorenzopalaia/Neural-Style-Transfer-and-Genre-Classification/issues
[license-shield]: https://img.shields.io/github/license/lorenzopalaia/Neural-Style-Transfer-and-Genre-Classification.svg?style=for-the-badge
[license-url]: https://github.com/lorenzopalaia/Neural-Style-Transfer-and-Genre-Classification/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/lorenzo-palaia-7177a5202
[product-screenshot]: images/screenshot.png