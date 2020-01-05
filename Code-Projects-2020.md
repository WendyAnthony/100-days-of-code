# Log for #100DaysOfCode - Round 1 - Wendy Anthony

**The log of my #100DaysOfCode challenge. Started on 2020-01-01**  
[My Code](https://github.com/WendyAnthony/100-days-of-code/tree/master/My-Code)

***
## Table of Contents  <a name="TOC"/>
- **[Week II](#weekII)**  
  - [R1D5 2020-01-05](#R1D5) 
- **[Week I](#weekI)**    
  - [R1D4 2020-01-04](#R1D4)  
  - [R1D3 2020-01-03](#R1D3)  
  - [R1D2 2020-01-02](#R1D2)  
  - [R1D1 2020-01-01](#R1D1)  
- **[Wishlist](#wishlist)**

***
# Week II <a name="weekII"/>
***
## R1D5 2020-01-05 <a name="R1D5"/>
**Today's Progress**: 
- trying to get iNaturalist to work in R ```library("rinat")```  
  - finally got my personal observations to show in R !!!

**Thoughts:** 
- tutorial samples work, but not with projects I'm involved with e.g. bc-parks  
  - bc-parks is an umbrella project with other individual BC Parks Projects
  - rinat gives an error; I've tried a few suggestions (a common error with rinat) but no luck so far

**Links to code work:** 
- to extract my personal observations  
  - ```get_inat_obs_user("wendy_anthony", maxresults = "3000")```
  - default is 110 results > I actually have 2200 uploaded observations between Aug 2019 & May 2015
- to Extract just research grade observations  
  - wa_inat_userstats_research <- wa_inat_userstats[which(wa_inat_userstats$quality_grade == "research" ),] 

[TOC](#TOC)
***
# Week I <a name="weekI"/>
***
## R1D4 2020-01-04 <a name="R1D4"/>
**Today's Progress**: 
- Continued work on UVic website
- Learning more about .md styling 
  - e.g. Table of Contents, list items
- trying ```eBird auk``` [auk](https://cran.r-project.org/web/packages/auk/vignettes/auk.html) package

**Thoughts:** 
- using examples from packages work fine (e.g auk), but when trying to import real data, not so much ...

**Links to code work:** 

[TOC](#TOC)
***

## R1D3 2020-01-03 <a name="R1D3"/>
**Today's Progress**: Fixed absolute URLs in UVic student website (over 2400 files)

**Thoughts:** Continued work with weather data to better understand how to process it

**Links to code work:**  http://people.geog.uvic.ca/wanthony/website/index.html 

[TOC](#TOC)
***

## R1D2 2020-01-02 <a name="R1D2"/>
**Today's Progress**: 
1. [x] Reworked ```Shiny App``` for UVic Census data, creating normalized value columns for comparing polygons (variable / #households)
2. [x] Figured out how to make windrose with weather data  

**Thoughts:** 

**Links to code work:**  
1. https://wendyanthony.shinyapps.io/VicCensusApp/
2. https://github.com/WendyAnthony/100-days-of-code/blob/master/My-Code/windrose.R

[TOC](#TOC)
***

## R1D1 2020-01-01 <a name="R1D1"/>
**Today's Progress**: Started a Weather App. Worked on the draft layout of the app, struggled with ```OpenWeather API```  

**Thoughts:** Coding takes patience and lots of trial-&-errors, then EUREKA!!

[TOC](#TOC)
<br />
***  
***
# Wish-List <a name="wishlist"/>  
- [x] Create log of coding work done as progress
- [x] Make UVic website responsive & with more up-to-date styling
- [x] Formatting md pages (like this one)
- [x] become more comfortable using ```github```
- Use eBird data
- Use iNaturalist data
- use historical weather data
- Shiny - add different choices
- learn to do more stuff with R [R Resource Links](https://wendyanthony.github.io/R_Stats_Links-io.html)

[TOC](#TOC)

