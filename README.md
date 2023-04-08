# Tips for TU Delft PhD Dissertation

## Writing
* Course T1.B3 [PROM-3 Writing a Dissertation](https://www.tudelft.nl/en/tpm/itav/education/courses-and-workshops-for-phd-students/prom-3-writing-a-dissertation-t1b3).
* Use a LaTeX template with a good page layout (enough binding offset, even top/bottom margin), such as [this](https://github.com/Inventitech/phd-thesis-template).
* Use ```ps2pdf``` to reduce PDF file size.


## Printing

Some printing companies
* [DAP​](https://www.delftacademicpress.nl/phd-thesis.php​)
* [Gildeprint​](https://www.gildeprint.nl/en/printing-thesis/​)
* [Ipskamp Printing, Enschede​](https://proefschriften.net/en/?utm_source=ips&utm_medium=website&utm_campaign=proefschrift_thesis​)
* [Proefschrift​](https://www.proefschriftspecialist.nl/thesis-printing​)
* [RidderPrint​](https://www.ridderprint.nl/en/thesis-printing/​)
​

RidderPrint, the one I used, provides sufficient information on the [website​](https://www.ridderprint.nl/en/thesis-printing/​), including:
* layout guidelines for thesis/cover/invitation/propositions.
* paper type, cover finishing options.
* workshops.
* ...


## Uploading to TU Delft Repository
In [repository](https://repository.tudelft.nl/islandora/search?collection=research&f%5B0%5D=mods_genre_s%3A%22doctoral%5C%20thesis%22), a cover page is added at the beginning the file you upload. 
The page numbers will be shifted.
The Python script here can pre-shift the page numbers reversely.
Please update the variables inside and run
```
python update_page_label.py
```

After uploading, you may download the thesis and check if
* the page number labels and
* the PDF outlines/bookmarks

are correct.
