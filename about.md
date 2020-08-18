---  
layout: page  
title: About  
---  
  
* ToC
{:toc}
  
## About the Project  
  
<div style="width: 50%; float: left;"> 
<a href="{{ site.baseurl }}/assets/images/cavendish-pageimage.jpg"><img src="{{ site.baseurl }}/assets/images/cavendish-pageimage.jpg" height="350" alt="cavendish page image"></a>  
</div>

<div style="margin-left: 50%;"> 
<a href="{{ site.baseurl }}/assets/images/transcribathon-flyer.jpg"><img src="{{ site.baseurl }}/assets/images/transcribathon-flyer.jpg" height="350"></a>
</div>

Margaret Cavendish (1623-1673) wrote numerous works of philosophy, plays, and poetry, as well as a science fiction work, an autobiography and a biography of her husband. While many of her works are available online, her 1663 edition of *Philosophical and Physical Opinions* has not yet had an open access and easily searchable edition until now. The work is important in that is it a substantial revision of her 1655 edition of *Philosophical and Physical Opinions*. The 1655 edition was a mere 174 pages, while the revised and expanded 1663 edition comes in at 510 pages including the unpaginated prefaces and index.  
  
Given the growing interest in Cavendish's philosophical works by  early modern scholars, it seemed it was time to make this work more widely available. It was clear that we needed to hand transcribe the work, but its length was too much for a small group to undertake. Thus, we decided to get help from the community by hosting a transcribe-a-thon on September 27, 2019. With support from [KU Institute for Research in the Digital Humanities](http://idrh.ku.edu), [KU Libraries](http://lib.ku.edu), and the KU [Philosophy Department](http://philosophy.ku.edu), as well as over 70 transcribers from around the world, the text was completely transcribed by October 4th, 2019.   
    
In transcribing the text, we decided to ignore most of the elements that were due to features of the printing of the book (such as running headers and hyphenations at the margins, catch words were ignored except when hyphenated), but the one feature of the book we did maintain was the pagination as this is valuable to scholars and students. We maintained the features of the text as written by Cavendish in that we followed Cavendish's spelling, capitalization, and punctuation.  We added notes to document Cavendish's corrections in the text as noted in the Errata.  
  
**If you have questions or comments about this project, please contact Marcy Lascano at <marcylascano@ku.edu>.**  

<p><a href="#top">&#x21a9;&#xfe0e; Return to top</a></p> 

---

## How we did it

In developing this project we were guided by principles of [minimal computing](https://go-dh.github.io/mincomp/) to create an electronic edition of the text that would be:

* lightweight (suitable for reading, downloading, and sharing);
* flexible (designed to be built upon with annotations and bibliographic enancements); and
* durable (easy to maintain with minimal risk of broken links or functonality). 

It also required that we do this with no budget.

Transforming the text from the scanned page of the 1663 edition (available in the Early English Books Online (EEBO) database) to a minimal full text edition involved two general stages of the project.

### Collaborative Transcription

The first step was to create editable, electronic text from the scanned page images. Optical character recognition (OCR) was not a viable approach due to the layout, structure and font of the original publication availabe in EEBO; it would have required too much reformatting and cleanup. Transcribing the text from scratch was the way to go, but at over 500 pages it was too long to for a single person or small group to achieve in a reasonable time period.


We decided to enlist the help of collaborators, both local and around the world, to transcribe the text online. Inspired by such crowdsouring transcription services as 
[From the Page](https://fromthepage.com/), Brian Rosenblum of the [IDRH](http://idrh.ku.edu) build a simple website to facilitate this process. Participants could select and "check out" a page and type a plain-text transcription following a set of instructions on how to capture and represent abbreviations, chapter headings, page numbers, ligatures, catch words, unclear text, and other elements in the book. On September 27, 2019 we launched the Cavendish Transcribe-a-Thon, open to participants locally at the University of Kansas and online to anyone who wanted to participate. 

<div style="width: 50%; float: left;"> 
<a href="{{ site.baseurl }}/assets/images/transcribe-screenshot2.jpg"><img src="{{ site.baseurl }}/assets/images/transcribe-screenshot2.jpg" height="250"></a>
</div>

<div style="margin-left: 50%;"> 
<a href="{{ site.baseurl }}/assets/images/transcribe-screenshot3.jpg"><img src="{{ site.baseurl }}/assets/images/transcribe-screenshot3.jpg" height="250"></a>
</div>

About 15 people participated in person over the course the day, sustained by coffee and donuts, and several dozen participants joined online, from Australia to the U.K. to California. Within a week the text was completely transcribed, with contributions by over 70 participants from around the world. All transcribers are listed below.

### Editing and *Ed.*

The second phase of the project included editing the transcriptions and publishing the text online. Using a simple text editor, Marcy Lascano worked through the text page by page to clean up the transcriptions, double checking against the original and resolving inconsistencies in formatting among the contributions of the 70 transcribers. She also added some basic structural formatting using [markdown](https://www.markdownguide.org/), a simple language for structuring plain text documents.

Meanwhile, Brian Rosenblum built the website using the [Ed publishing platform](https://minicomp.github.io/ed/). Ed is designed specifically for minimal scholarly or reading editions and contains templates for publishing prose, poetry and drama in elegant, flexible formats meant to be easy to maintain and share. Ed itself is built on Jekyll--a static website generator that turns our markdown-structured text into static HTML pages that can be published directly online without the need for a database-dependent back end, or for the often complex set of processes needed to create and maintain other markup-based digital editions. 

Conceived and created by [Alex Gil](https://www.elotroalex.com/profile/) at Columbia University, Ed is designed to be a low-cost but highly functional platform that enables the kind of text recovery work undertaken here in the Cavendish project. 

### Plain text, github project, and digital tools

The markdown-structured plain text, and the entire Ed/Jekyll projects files, are available on the [digital tools]({{ site.baseurl }}/digital-tools.md) page of this website, along with some links to web-based tools for visualization, analysis, and annotation.

<p><a href="#top">&#x21a9;&#xfe0e; Return to top</a></p>  
---

## Acknowledgments   
    
This project was made possible by the generous support of the University of Kansas Philosophy Department and Institute for Research in the Digital Humanities. Special thanks goes to Brian Rosenblum for setting up the transcription site and the final Ed. site, as well as providing other technical guidance and expertise. In addition, a debt of gratitude goes to Rachel Henderson, the project research assistant, who worked tirelessly on various aspects of the project, and to David Tamez in IRDH who helped with the transcribe-a-thon. A special thanks goes to Jon Shaheen for re-starting the Cavendish Reading Group in the Spring of 2020 and for passing along a weekly typo list. Finally, thank you to all the transcribers who put in their time to help make this text available:  

Ada Emmett  
Alex Riedel  
Alexandra Kennedy  
Alison Peterman  
Andrew Mills  
Armin Schulz  
Brad Cokelet  
Brian Rosenblum  
Carmen Orth-Alfie  
Carolyn Caine  
Christopher P. Noble  
Dale Dorsey  
David Sanson  
David Tamez  
Deborah Boyle  
Dwight Lewis  
Eileen Nutting  
Elspeth Healey  
Emily Cook  
Ericka Tucker  
Evan Rodriguez  
Gary Ostertag  
Greta Valentine  
Issei Takehara  
Jada Elder-Wilkerson  
Jason Raibley  
Jill Hernandez  
John Komdat  
Jonathan L. Shaheen  
Jonathan P. Lamb  
Joseph Penczak  
Julia Jorati  
Julie Klein  
Justina Mercado   
Kelin Emmett  
Kevin Watson  
Larry M. Jorgensen  
Liz Goodnick  
Maks Sipowicz  
Margaret Atherton  
Mary Ann Baker  
Mary Bifulco  
Mary Crosson  
Michael Bennett McNulty  
Michael J Trout  
Michael Rosenthal  
Nadia Ruiz   
Nastassja Pugliese  
Natalie Sextro  
Nathanael Smith  
Noah Greenstein  
Pat McConville  
Phil Tran  
Qiu Lin  
Rachel Henderson  
Renata Martins Prado Matos Augusto  
S. Joyner  
Saron T. Tran  
Scott Hanrath  
Thomas Morrison  
Tim Black  
Timothy Yenter  
Torin Doppelt  
Trevor Pearce  
Wiebke Deimling  
William A. B. Parkhurst  
William Miller  
And thanks to those who transcribed anonymously as well!  

<p><a href="#top">&#x21a9;&#xfe0e; Return to top</a></p>  
