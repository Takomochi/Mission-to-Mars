# Mission to Mars

## Overview of the project
This project is about scraping the information about Mars from websites and creating a web application to present that information. We show the latest news on our web application, featuring Mars images, Mars Facts, and Mars hemispheres.

### Files for the project:
1. [Mission_to_Mars_Challenge.ipynb](https://github.com/Takomochi/Mission-to-Mars/blob/main/Mission_to_Mars_Challenge.ipynb) (Create codes for web scraping)
2. [scrape.py](https://github.com/Takomochi/Mission-to-Mars/blob/main/scraping.py) (Create functions to extract web information)
3. [app.py](https://github.com/Takomochi/Mission-to-Mars/blob/main/app.py) (Create a web page with Flask)
4. [index.html](https://github.com/Takomochi/Mission-to-Mars/blob/main/templates/index.html) (Customize the website with Bootsrap)

## Resouces
- Data: [Mars Planet Science](https://redplanetscience.com/), [JPL Space Images](https://spaceimages-mars.com), [Mars Facts](https://galaxyfacts-mars.com), [Hemisphere images](https://marshemispheres.com/)
- Software: Python 3.7.10, Juputer Notebook, MongoDB

## Results
Screenshot below is the website. When you click the "Scrape New Data" button, all the information (News title, paragraph, Featured image, Mars Facts, and Hemispheres) will be updated.

<img width="589" alt="screenshot_1" src="https://user-images.githubusercontent.com/85041697/147887930-5f9f11cb-4d33-4676-9529-ffbf069bdbea.png">
<img width="581" alt="screenshot_2" src="https://user-images.githubusercontent.com/85041697/147887933-ad93fc2d-7f18-4ccb-bb07-9fa98e7fc27a.png">


### Bootsrap 3 Component

1. Mobile-Responsive
In order to make the website to be mobile-responsive, I added Bootsrap 3 grid system. <br>
- **col-sm-6** : Featured Mars image and Mars facts
- **col-sm-3**: Mars hemispheres

2. Styling website
For the stylying, I used 2 Bootsrap 3 components. 
- **btn-lg** : Resizing the button
- **thumbnail**:  Mars hemishere images

    Now the website looks like the image below for iPad users.<br>

    <img width="315" alt="responsive" src="https://user-images.githubusercontent.com/85041697/148272584-a53a7938-629d-43ee-9482-7a22c71ad996.png">
