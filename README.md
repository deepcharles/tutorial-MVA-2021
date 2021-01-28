# Tutorials for the "Machine Learning for Time Series" class (Master 2 MVA, 2020-2021)

([Course description.](http://www.laurentoudre.fr/ast.html))

## General information

<details>
<summary>Requirements</summary>

These tutorials use Python 3 (version 3.6 at least) and [Jupyter notebooks](https://jupyter.org/).
You will also need several Python packages that are listed in `requirements.txt` files in the relevant folders.

### With  `pip`
All packages can be installed using `pip install package_name`.

### With `conda`

Most packages should also be available through `conda`, however I have not verified it.
At least one package (`loadmydata`) is not available through `conda`.
To install it, run (within a conda environment) `conda install pip` then `pip install loadmydata`. (See [the conda documentation](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-pkgs.html#installing-non-conda-packages) for more information.)

</details>

<details>
    <summary>Communicate</summary>

Please feel free to open an issue if you think something is wrong or could be improved!
To that end, go to the [Issues](https://github.com/deepcharles/tutorial-MVA-2021/issues) section of this repository.
</details>


## Tutorials 1 and 2

Friday 29<sup>th</sup> January 2021

Themes:
- Convolutional dictionary learning
- Dynamic time warping
- Feature extraction and selection
