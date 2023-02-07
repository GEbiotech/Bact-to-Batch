# Bact-to-Batch


The **Bact-to-Batch** repositorty helps you create dynamic analysis documents that combine code and rendered output (such as figures) to generate the complete analysis described in this study : <i>Bact-To-Batch: a microbiota-based tool to determine optimal animal allocation in experimental designs</i> . 

## Article

Currrently under submission : <i>Bact-To-Batch: a microbiota-based tool to determine optimal animal allocation in experimental designs</i> 

## Installation

The easiest way to use the **Bact-To-Batch** markdown is from within the [RStudio IDE](https://posit.co/download/rstudio-desktop/), but you don't need to explicitly install it or load it, as RStudio automatically does both when needed. 

If you want to use the rmarkdown package outside of RStudio, you can install the package from CRAN as follows:

```r
install.packages("rmarkdown")
```

If you want to use the development version of the rmarkdown package (either with or without RStudio), you can install the package from GitHub via the [**remotes** package](https://remotes.r-lib.org):

```r
remotes::install_github('rstudio/rmarkdown')
```

If not using the RStudio IDE, you'll need to install a recent version of R (>= 4.1.1);


## Usage

The easiest way to make a new R Markdown document is from within RStudio. Go to _File > New File > R Markdown_. From the new file wizard, you may:

Once inside your new `.Rmd` file, you should see some boilerplate text that includes code chunks. Use the "Knit" button in the RStudio IDE to render the file and preview the output with a single click or use the keyboard shortcut Cmd/Ctrl + Shift + K. 

You can also click "Knit to HTML" again to render the full document with all code chunks.

The HTML output is also provide in the HTML folder of the project, so you can have a look to the final output.

## Getting help

Feel free to contact the author of the publication once published


