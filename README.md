# Singaporean hawkers are digitizing, but not everyone is keeping pace.
## Lede Program 2025 - Project 2 

This is my submission for Lede 2025's second project. The aim of this projectr is to determine, by means of Google Maps stall listings, the extent of hawker digitization in Singapore and whether the digitization push has been equitable. The project does so by scraping Google Maps listings, classifying them by planning area with / without new flat developments and mapping them out to see if listings are concentrated in any particular town. 

In Singapore, the hawker digitization push has struggled to gain momentum for years. Despite numerous government and private sector-led initiatives, many hawkers still resist digitization due to age and slim profit margins. One example is how food delivery platforms are eager to onboard hawkers - but charge them a hefty commission fee that goes as high as 30% of the order value. 

This is a problem that has persisted for nearly half a decade. Recently however, mainstream media narratives claim that more hawkers are going digital. This claim, however, contradicts several on-the-ground interviews, where older hawkers still overwhelmingly prefer cash payments and prefer to remain unexposed to technology. Therefore, this project aims to investigate the veracity of this claim, and assess what the ground reality is. 

These are my data sources: 

| What I plotted  | Data source |
| ------------- | ------------- |
| Chicken rice stall listings | Google Maps Search Results | 
| List of Planning Areas in Singapore| [Wikipedia](https://en.wikipedia.org/wiki/Planning_areas_of_Singapore) | 
| Map of Planning Area shapes | [Singapore Master Plan 2019 Planning Area Boundary](https://en.wikipedia.org/wiki/Planning_areas_of_Singapore) | 

The CSV files used in this project are as follows: 

|Name | Description | 
| ------------- | ------------- |
|sg-chicken-rice-timecleaned.csv | Contains cleaned data on chicken rice listings collected via Google Maps| 
|sg-chicken-rice-by-area.csv | Contains data of chicken rice listings in Singapore grouped by planning area | 


The data suggests that chicken rice stalls in Singapore with an online presence are overwhelmingly located in areas that have new flat development and renovation projects. These also happen to be areas that the younger generation of hawkers, or "hawkerpreneurs" as they are locally called, tend to operate in. 

The story webpage is here: [https://tianwen-tay.github.io/tianwen-tay-project2/](https://tianwen-tay.github.io/tianwen-tay-project2/)

## Skills learnt 

- Applying a header banner and embedding video using HTML
- using regular expressions to handle unclean data
- Properly creating a map with datawrapper!
- Not wasting time trying to create and re-create a DIY Google Scraper when a free one does the job well enough 
  
## Things I would've liked to do: 

I would have liked to include some scrollytelling elements in this story - headlines decrying hawker digitization woes since 2017 to the present before getting into the gist of the story was what I had in mind. 
