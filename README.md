<!-- ABOUT THE PROJECT -->
# Alfa_Romeo_F1_Image_Scraper

This script will scrape Alfa Romeo F1 Wallpaper images from Alfa Romeo's F1 website. These artworks are created to promote each race weekend. There are currently 43 image available for download (updated: 2022-11-19).

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/willocov/Alfa_Romeo_F1_Image_Scraper">
    <img src="samples/AlfaRomeoSample.png" alt="landscape_sample">
  </a>
  
</div>

TO DO LIST:
1. Allow custom filename output
2. Create smarter default filenames (parse race name out of url)

<!-- GETTING STARTED -->
## Getting Started
Download requirements.txt and AlfaRomeoF1ImageScraper.py

### Prerequisites

Install Requirements
* pip
  ```sh
  pip install -r requirements.txt
  ```

Alternative method for installing beautifulsoup if requirements.txt has an issue:
* pip
  ```sh
  pip install bs4
  ```

<!-- USAGE EXAMPLES -->
## Usage

Images will be saved to the same directory as the script by deafult. 
A relative or absolute filepath can be passed as a parameter to specify the output directory. 

Same directory as script:
  ```sh
  python AlfaRomeoF1ImageScraper.py
  ```

Save to a specified directory using a relative filepath:
  ```sh
  python AlfaRomeoF1ImageScraper.py output/
  ```

Save to a specified directory using a relative filepath:
  ```sh
  python AlfaRomeoF1ImageScraper.py C:\Users\test\Downloads\
  ```

<!-- Disclaimer-->
## Disclaimer

I do not own these images. These images are used for educational purposes under Fair Use Copyright laws.





