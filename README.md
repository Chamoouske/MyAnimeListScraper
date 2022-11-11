<div align="center" class="title">

# Scraper [MyAnimeList.net](https://myanimelist.net/)

</div>

<div align="justify" class="details">

This project is a web scraper for [MyAnimeList](https://myanimelist.net/), a website with details of animes. This scrapper collects name, score, genres, themes, studio and other information about the animes.

</div>

<div align="center" class="badges">

[![GitHub issues](https://img.shields.io/github/issues/Chamoouske/MyAnimeListScrapper?style=plastic)](https://github.com/Chamoouske/MyAnimeListScrapper/issues) [![GitHub forks](https://img.shields.io/github/forks/Chamoouske/MyAnimeListScrapper?style=plastic)](https://github.com/Chamoouske/MyAnimeListScrapper/network) [![GitHub stars](https://img.shields.io/github/stars/Chamoouske/MyAnimeListScrapper?style=plastic)](https://github.com/Chamoouske/MyAnimeListScrapper/stargazers) [![GitHub license](https://img.shields.io/github/license/Chamoouske/MyAnimeListScrapper?style=plastic)](https://github.com/Chamoouske/MyAnimeListScrapper/blob/main/LICENSE)

</div>

---

<div align="center" class="navigation-title">

## Navigation Menu

</div>
<div class="navigation">

-   [Scraper [MyAnimeList.net]](#scraper-myanimelistnet)
    -   [Navigation Menu](#navigation-menu)
    -   [Getting Started](#getting-started)
        -   [Prerequisites](#prerequisites)
    -   [Usage](#usage)
    -   [Built With](#built-with)
    -   [Contribution](#contribution)
    -   [License](#license)
    -   [Author](#author)
    </div>

---

<div align="center" class="installation-title">

## Getting Started

</div>
<div align="justify" class="installation">

### Prerequisites

-   [Python 3.8](https://www.python.org/downloads/) or higher

### Dependencies

Follow this steps to install the dependencies if you don't have installed [Anaconda](https://www.anaconda.com/products/individual) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html). If you have installed Anaconda or Miniconda, you can skip this step.

> This step is optional.
>
> -   Create a virtual environment
>     > ```bash
>     > python -m venv venv
>     > ```
> -   Activate the virtual environment
>     > -   Windows
>     >     > ```bash
>     >     > venv\Scripts\activate
>     >     > ```
>     > -   Linux
>     >     > ```bash
>     >     > source venv/bin/activate
>     >     > ```

-   To install the dependencies, run the following command:

```bash
pip install -r requirements.txt
```

Now you can open archives with Jupyter, if [Anaconda](https://www.anaconda.com/products/individual) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) is installed, or open with [VsCode](https://code.visualstudio.com/) using recommended extensions.

> PS: The recommended extensions are:
>
> -   [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
> -   [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)

</div>

---

<div align="center" class="usage-title">

## Usage

</div>
<div align="justify" class="usage">

Some notebooks just works with after executing the code in the previous notebooks.

Order to execute notebooks:

-   1-[`GetAllAnimes.ipynb`](./GetAllAnimes.ipynb). Execution time: 30min to 1h (depends on your internet connection and `RANGE_LIMIT` value, default: `100000`)
-   2-[`GetGenreThemeForAnimes.ipynb`](./GetGenreThemeForAnimes.ipynb). Execution time: 15min to 16h (depends on the number of animes collected in the previous notebook and your internet connection)
-   3-[`PrepareDataset.ipynb`](./PrepareDataset.ipynb) (optional). Execution time: 1min to 5min

The others notebooks haven't dependencies to others notebooks.

</div>

---

<div align="center" class="usage-title">

## Built With

</div>
<div align="justify" class="usage">

-   [Python](https://www.python.org/)
-   [Jupyter](https://jupyter.org/)
-   [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
-   [Pandas](https://pandas.pydata.org/)
-   [Numpy](https://numpy.org/)
</div>

---

<div align="center" class="contribution-title">

## Contribution

</div>
<div align="justify" class="contribution">

If you want to contribute to this project, follow the steps below:

-   Fork this repository
-   Create a branch with your feature: `git checkout -b my-feature`
-   Commit your changes: `git commit -m 'feat: My new feature'`
-   Push to your branch: `git push origin my-feature`
</div>

<div align="center" class="license-title">

---

## License

This project is under the MIT license. See the [LICENSE](./LICENSE) file for more details.

</div>

---

<div align="center" class="author-title">

## Author

![Chamoouske](https://github.com/Chamoouske.png?size=200)

Made with ❤️ by [Chamoouske](https://github.com/Chamoouske)

[![Twitter Badge](https://img.shields.io/badge/-@chamoouske-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/chamoouske)](https://twitter.com/chamoouske) [![Linkedin Badge](https://img.shields.io/badge/-Ajax%20Lima-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/ajaxlima/)](https://www.linkedin.com/in/ajaxlima/) [![Gmail Badge](https://img.shields.io/badge/-ajaxlima94@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:ajaxlima94@gmail.com)](mailto:ajaxlima94@gmail.com)

</div>
