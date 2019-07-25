# Data School poster templates

Attempt at some poster templates based on [posterdown](https://github.com/brentthorne/posterdown) 
with a Data School flavour. To create a poster:

1. Install [posterdown](https://github.com/brentthorne/posterdown)
At the R-studio interactive prompt, type:
* install.packages("glue")
* install.packages("devtools")
* devtools::install_github("brentthorne/posterdown")

2. Clone this repository to a location on your computer where you would like to make your poster(s).

3. Create a copy of the `demo.Rmd` file, name it after your specific poster, and edit the content. Note: this needs to be in the same location as the `demo.Rmd` file.

An example of the output from the `demo.Rmd` file can be found in the `example` folder as a PDF. 
Since the page is built around the A0 scaled background image, printing the page to a PDF from the 
browser is the best way to see how everything looks at the "right" page size since fiddling
around with window sizes on the screen can be difficult. 

In addition, if you wish to knit the `demo.Rmd` directly, you will need to make sure you have the
`tidyverse`, `gapminder`, `gganimate`, `gifski`, `png`, and `kableExtra` packages installed. The first time you knit
will take a minute or two because of the animation rendering, but this step is cached so will not be
run again unless you change the animation code. 

Synthesis Project Poster - Seija

- Acqquire isotherm data from UNSW Library, as a CD-ROM
- Data comes as a pdf file
- Transform pdf -> csv on line https://www.pdftoexcel.com/, a drag and drop, free and quick service. Mine was 156 pages and it took about 2 minutes.
- Extract rlevant tables from the csv document 
- 
- 
