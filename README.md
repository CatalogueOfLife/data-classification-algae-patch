# Catalogue of Life Algae Classification Patch

A small dataset that acts as a gap filler in extended releases for the Algae management classification of the Catalogue of Life.
https://www.checklistbank.org/dataset/304143/about


## Files
The main taxonomy tree lives in [taxonomy.txtree](taxonomy.txtree). 
Information about the dataset as a whole and how to cite it is kept in metadata.yaml,
while you can curate a list of structured references either in [BibTex](reference.bib) or [TSV format](reference.tsv). 
References from this list can then be [cited in the taxonomy file](https://github.com/CatalogueOfLife/coldp/blob/master/docs/publishing-guide-txtree.md).
Please remove unused files in your copy.

BibTex content can be retrieved from CrossRef for most DOIs when known.
For example by using curl on the terminal like this:
> curl --location --silent --header "Accept: application/x-bibtex" https://doi.org/10.1080/11035890601282097 
> @article{Eriksson_2006,
    doi = {10.1080/11035890601282097},
    url = {https://doi.org/10.1080%2F11035890601282097},
    year = 2006,
    month = {jun},
    publisher = {Informa {UK} Limited},
    volume = {128},
    number = {2},
    pages = {97--101},
    author = {Mats E. Eriksson},
    title = {Polychaete jaw apparatuses and scolecodonts from the Silurian Ireviken Event interval of Gotland, Sweden},
    journal = {{GFF}}
}

There are also online editors, e.g. https://truben.no/latex/bibtex/#

Using Mendeley or Zotero can also be used to collaboratively manage references and export them to a BibTex file to be used in the repository.
