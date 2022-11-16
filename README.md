# G.A.R.C.

G.A.R.C. stands for General Aviation Report Creator, it is a Python app (Dash) that allows to download from anywhere the related DB of flights, makes various analysis and render them in a web page that runs in localhost.

**ATTENTION**
This repository is just for this readme file to show the mode of operation.

## The data
Data are stored in an encrypted server that it's contacted each time the app is evoked, they are keeped in a local variable that evanish each time the app is closed.
This has been made for two main reasons:
- Security
- Lightness


![Alt text](https://github.com/MaurizioCarrara/GARC-Public-/blob/main/GIFs/downloadDB.gif)



## Structure
In the actual version (2.1), there are two selectors (data range and airport) that filter the downloaded data and just one page with all the charts and tables (5 A4 pages in printing).


![Alt text](https://github.com/MaurizioCarrara/GARC-Public/blob/main/GIFs/Selectors.gif)

## Future features (v 3.0)
- Linear regression charts for movments and MTOW (maximum take-off weight)
- Rate of change chart 
- Multipage

## Known issues
- Time of loading depends on the hardware
- Functions and classes will be improved to higher efficency
