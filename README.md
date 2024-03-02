<a name="readme-top"></a>
<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/lorenzopalaia/Neural-Style-Transfer-and-Genre-Classification">
    <img src="repo_assets/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Neural Style Transfer & Genre Classification</h3>

  <p align="center">
    The project aims to create a classifier of musical genres and to perform a neural style transfer between two audio tracks using spectrograms
    <br />
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<!--
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>
-->


<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Preview][product-preview]](https://example.com)

Project was developed for "Laboratorio di Intelligenza Artificiale" class, Ingegneria Informatica e Automatica, Università La Sapienza

Two different approaches were used for the classification, one based on Image Augumentation technique and another that uses the features of the audio tracks stored in a .csv file. For the first approach PyTorch was used while there is an implementation in PyTorch and one in Tensorflow for the classification through features. Similarly, there are implementations in both frameworks for neural style transfer

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [Colab](https://colab.research.google.com/)
* [PyTorch](https://pytorch.org/)
* [Tensorflow](https://www.tensorflow.org/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Datasets

#### Neural Style Transfer

Already provided

#### Genre Classification

Download GTZAN dataset [here](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification), unzip it and replace the GTZAN Dataset (Reduced) folder

### Installation

[!] WIP: migrate installation from Colab to local environment

The whole project is structured to be run through Google Colab with the datasets uploaded to Google Drive. In particular, it is necessary to download the datasets and structure the Google Drive folders as follows by inserting the `Colab Notebooks` folder in the Google Drive home:

```
.
├── data
│   ├── input
│   │   ├── NST
│   │   └── GC
│   │       └── GTZAN Dataset (Reduced)
│   └── output
│       └── NST
│           ├── PyTorch
│           └── Tensorflow
├── test
├── models
│   ├── PyTorch
│   │   ├── GC_csv
│   │   ├── GC_audioaug
│   │   └── GC_imgaug
│   └── Tensorflow
│       └── GC_csv
├── models
│   ├── csv
│   │   └── GC_pytorch_tensorflow_csv.ipynb
│   └── Data Augmentation
│       ├── GC_pytorch_img.ipynb
│       └── GC_pytorch_audio.ipynb
└── NST
    ├── NST_plots.ipynb
    ├── NST_pytorch.ipynb
    └── NST_tensorflow.ipynb
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Run a notebook from `NST` or `GC` folder using the GPU runtime provided by Colab whenever possible

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [ ] Convert scripts to Tensorflow v2.0

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Lorenzo Palaia - lorenzopalaia53@gmail.com

Project Link: [https://github.com/lorenzopalaia/Neural-Style-Transfer-and-Genre-Classification](https://github.com/lorenzopalaia/Neural-Style-Transfer-and-Genre-Classification)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
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
[linkedin-url]: https://linkedin.com/in/lorenzopalaia
[product-preview]: repo_assets/preview.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 