# Webtoon Popularity and Reader Engagement

## Overview

This project analyzes what drives readership on Webtoons, one of the largest 
digital comics platforms in the world. I scraped 1,538 titles directly from 
the platform and examined genre distribution, viewership, subscriber counts, 
update schedules and age ratings to identify patterns in how readers discover 
and engage with content.

The dataset used in this analysis was scraped using Python and is available 
here: https://github.com/SaiAbhignaTalla/web_scraping_using_python

## What the Data Shows

Romance and Fantasy are the most published genres on the platform with 354 
and 305 titles respectively. However, publication volume does not predict 
viewership. Slice of Life, with only 71 titles, generates the highest average 
views per title of any genre. This suggests that readers are drawn to 
relatable everyday storytelling in a way that outpaces more saturated genres.

To measure engagement more precisely, I created a derived metric called Views 
per Subscriber. This captures how often readers return to a title relative 
to how many have formally subscribed, which is a stronger indicator of 
habitual readership than raw view counts. My Giant Nerd Boyfriend and 
Bluechair lead this metric by a significant margin, both in the Slice of 
Life and Comedy categories.

The scatter plot of total views against total subscribers reveals a strong 
positive relationship across the dataset. Titles like Lore Olympus, True 
Beauty and unOrdinary sit at the top of both axes. A small number of outliers 
including My Giant Nerd Boyfriend and The God of High School accumulate 
unusually high view counts relative to their subscriber base, indicating 
a pattern of casual but repeated readership that subscriber count alone 
does not capture.

Update schedule also shows a clear pattern. Titles that publish on Tuesday 
generate the highest total views across the dataset, with Monday close behind. 
Viewership declines steadily from Thursday through the weekend. This is 
consistent enough across the dataset to suggest that early week publishing 
has a measurable impact on reach.

## Limitations

The dataset is a single point in time snapshot. Titles that have been on 
the platform longer naturally accumulate more views, which introduces bias 
into genre level comparisons.
