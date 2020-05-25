# Installation


## With GPU support

=== "conda"
    ``` bash
    conda install tensorflow-gpu=2.1.0
    ```

=== "R"
    ``` r
    install.packages("tensorflow")
    tensorflow::install_tensorflow(version = "2.1.0-gpu")
    ```
    `install_tensorflow` is a wraper around `reticulate::py_install`. Please refer to [Installing Python Packages](https://rstudio.github.io/reticulate/articles/python_packages.html) for more information.


## Without GPU support

=== "conda"
    ``` bash
    conda install tensorflow-gpu=2.1.0
    ```

=== "R"
    ``` r
    install.packages("tensorflow")
    tensorflow::install_tensorflow(version = "2.1.0")
    ```
    `install_tensorflow` is a wraper around `reticulate::py_install`. Please refer to [Installing Python Packages](https://rstudio.github.io/reticulate/articles/python_packages.html) for more information.
