# cookiecutter-quarto-snakemake-workflow

Cookiecutter template for snakemake workflows and quarto. 

Blog created with

```
quarto create-project --type website --template blog
```


### INSTALL

Install cookiecutter:

```
pip install cookiecutter
```

Start creating a snakemake-workflow from cookiecutter:
```
cookiecutter https://github.com/daiuc/cookiecutter-quarto-blog-smk.git
```


### CREATE BLOG POSTS OR WEB PAGES

Use Rstudio or your favorite IDE to create `*.qmd` files and render. Rendered html files are automatically saved in `docs`, which can be set up for gh-page.

- Note for blog posts, create a folder for your article, and in it, create a `index.qmd` file. 

- For regular web pages, create a folder under root, a landing page, e.g. `index.qmd`. Modify navbar and start adding pages.


### SNAKEMAKE PIPELINES

All snakemake pipeline stuff reside under `code`, that includes your data files in `resources` and `results`. By default `resources` and `results` are ignored from `git`. 

