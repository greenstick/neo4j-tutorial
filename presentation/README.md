# Neo4j and DREAM Challenge Presentation

This is a RMarkdown presentation explaining what Neo4j is all about and also
highlights the DREAM Challenge [Disease Module Identification][dmi], which will
be used as a use case for using Neo4j.

[dmi]: https://www.synapse.org/#!Synapse:syn6156761

## Compiling Prerequisites

* RStudio (Recommended for ease)
* `rmarkdown` R package

## Compiling

Within RStudio, open `neo4j-presentation.Rmd` and click "Knit HTML" button.

On command line, run the following.

```shell
Rscript -e 'rmarkdown::render("neo4j-presentation.Rmd")'
```
