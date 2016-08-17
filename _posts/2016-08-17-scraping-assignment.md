---
layout: post

title: Homework assignment--scraping exercise
description: Homework assignment

author: Claire Donnelly
email: clairedonnelly2016@u.northwestern.edu
twitter: _clairetweets
---

This week, I decided to scrape some Craigslist data to see what kinds of things people in the Washington, D.C. area are selling--specifically what kinds of musical instruments they're selling! Despite import.io being kind of a pain to work with, after my third try I did manage to set up a successful scraper that pulled data from the Craiglist page. To get the cleanest, most reliable data to start off with and to make less work for myself in cleaning the data, I went to the D.C. "For Sale" page on Craiglist, found the specific page for "musical instruments" and then checked the box off to the side that said "has image." (Generally, I find that checking the "has image" box gets rid of lots of spammer/robot Craigslist ads, but obviously this changes the data set and could have removed some legitimate listings. Is there a way to tell the scraper to skip over certain words or something? Then maybe I could identify some key spammer words and tell it to skip over those listings. I realized in doing this exercise that there is sort of a human element that might be necessary in screening data like things from Craigslist.)

Original data source url: http://washingtondc.craigslist.org/search/doc/msa?hasPic=1
(plus 5 additional pages that I added using the multiple url scrape function on import.io)

In analyzing the data, which I have in a Google spreadsheet linked below, I found some pretty interesting information. By sorting the musical instruments "Z to A" in the "price" column, I found that the most expensive musical instrument listed on the Washington D.C. Craigslist (of the listings that have pictures) is for sale for $79,900 and is a 1932 Steinway Model D Concert Grand Piano that is fully restored. By sorting "price" "A to Z" it appeared that the six cheapest things for sale in the instruments category all cost $1. But, after visiting the listing urls I realized that these Craigslist sellers were just using the $1 cost as a placeholder and that the price wasn't accurate. The next cheapest listing is a $10 harmonica from a blues band. 

