# Assignment3 | Collecting Data
## MA Digital Humanities | University of Groningen
### Corpus information
The corpus comprises 11 pictures of afternoon dresses, showing the progression of fashion from the early 1830s to the beginning of the 20th century, accompanied by a description (when available) and other relevant information. The gowns, although currently not on public view, are owned by the Metropolitan Museum of Art in New York and take part of the over 33 thousand fashionable dresses and accessories belonging to the Costume Institute’s collection.  
The corpus does not contain all the afternoon dresses in the collections, nonetheless aims to give an overview of such masterpieces of tailoring, encouraging students, scholars, or enthusiasts to further explore the whole collection.

### Scraped data
The data is sourced from the website of the Metropolitan Museum of Art, which provides open access to selected parts of its digitalized extensive collection. (www.metmuseum.org)
As previously mentioned, the scraped data include the object's title, its description (when available), the associated culture of origin, the year of creation, and the direct URL to the costume’s image as available on the MET website.

### Cleaning steps and file format
The only text cleaning step performed was whitespace stripping, no additional processes were necessary. Upon completion of the code execution, the data was saved in a CSV file. 

### Terms and Conditions
The following sections are provided verbatim from the Museum’s Terms and Conditions webpage, stating the open access condition of selected materials and the subsequent permission to scrape them. 

"Copyright and Proprietary Rights. 
The text, images, trademarks, data, audio files, video files and clips, software, documentation or other information contained in these files, and other content on the Websites (collectively, the "Materials") are proprietary to the Museum or its licensors unless identified by an Open Access (OA) icon. Materials identified as OA are either those that the Museum believes to be in the public domain, or those to which the Museum waives any copyright it might have. Copyright and other proprietary rights may be held by individuals or entities other than, or in addition to, the Museum.
[…]
a) Materials Identified as Open Access. By waiving any rights to Materials identified as Open Access, the Museum makes those Materials available for any purpose, including commercial and noncommercial use, free of charge and without requiring permission from the Museum. Open Access works are made available under a Creative Commons Zero (CC0) license."

Metropolitan Museum of Art. (2018, October 25). Terms and Conditions. Retrieved December 8, 2024. https://www.metmuseum.org/policies/terms-and-conditions 

### robots.txt file
'#' metmuseum.org/ 

user-agent: *
disallow: /sitecore
disallow: /sitecore_files
disallow: /sitecore modules
disallow: /app_config
disallow: /temp
disallow: /upload
disallow: /ghidorah
disallow: /style-guide
disallow: /style

user-agent: Pinterest
Crawl-delay: 1

sitemap: http://www.metmuseum.org/sitemaps/sitemap_index

