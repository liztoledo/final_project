# Makeup for all? A look into the diversity of shades, price points, and accessibility for foundations.
#### Final Project for Liz Toledo


### My Relationship to Makeup
For as long as I can remember, makeup has been a big part of my life. From watching my mother apply makeup every morning when I was a toddler to finally applying a sharp black eyeliner wing. Makeup is increasingly becoming more diverse and inclusive than it used to be in terms of the founders, trends, audience, and the products themselves. To those that are not as familiar with makeup, the entire process can be real complicated. And as if weren't precise or complicated enough, finding a foundation shade is ESSENTIAL. However, shade range has been historically skewed more towards lighter shades for reasons I may not go into full detail, but are part of Western society's ingrained anti-blackness. 

Now a days though, it seems like diversity and inclusiviy is a conversation that is taking place much more than it did before in the beauty community. From what I can remember, Rihanna's Fenty Beauty launch made headlines in 2017 for releasing 40 "Pro Filt'r" shades at once and having a wide range. Up until that point, not many makeup brands had achieved what Rihanna did for her brand's release. In fact, the drug store favorite Maybelline "Fit Me" launched more shades around the same time as the Fenty Beauty release, most of which were darker shades.

As makeup user, I recognize foundation can be one of the trickiest products to match to one's skin. It can either be great or a flop. Growing up, I used to be tanner and darker than I am today. I remember not being able to find an affordable foundation for me, unless I accompanied my mom to MAC for some samples. Because I am not as skilled or have the sufficient funds to splurge I had to learn to be choosy about which foundations where worth it in regards to size, color match, price, and now the brand's beliefs. I figured, if it was somewhat hard for me to find a color match, it's probably even harder for darker complexions to find a match at an affordable price if that.

### My Data Analysis Process

Initially, I planned to use a dataset from one of the given sources, but I couldn't find one that caught my eye as much as this one. I came across this dataset through a publication on the internet and to my surprise they linked their data at the very bottom. 

* The Pudding "[Diversity of Makeup Shades](https://pudding.cool/2018/06/makeup-shades/)" published in 2018
* Link to Makeup Data Used for the publication on [Github](https://github.com/the-pudding/data/tree/master/makeup-shades).

The Original data only contained one sheet, which was the "shades" sheet pictured below. Given my multiple analysis questions though, I decided to create separate sheets to include critical pieces of data such as the the price range of the products (respective to their countries), where/how the product can be bought, and a system to categorize the lightness range.


![Screenshot of Google Spreadsheets with list of extra sheets added by me.](https://media.journalism.berkeley.edu/upload/2020/08/15971832006a769bd.png)

In order to connect the data I researched separately, I found it most helpful to use the following formulas:
```
=VLOOKUP(I2, 'L-categorization'!$A$2:$B$101, 2, FALSE)
```
```
=VLOOKUP(K2, 'analysis-group'!$A$2:$B$9, 2, FALSE)
```
```
=VLOOKUP(A2, 'price-range'!$A$2:$B$37, 2, FALSE)
```
```
=VLOOKUP(A2, 'product-availability'!$A$2:$B$37, 2, FALSE)
```

## Lightness Categorization

Before I continue with the rest of the analysis, it is worth noting that this lightness categorization system will be helpful in better interpreting my points about shade range and lightness categorization. Hopefully, this isn't too confusing, but if it is feel free to look at the csv file.

| Lightness     | Category      |   
| ------------- |:-------------:|
| 0-20          | dark          | 
| 21-40         | medium-dark   | 
| 41-60         | medium        |
| 61-80         | light-medium  | 
| 81-100        | light        | 

## Foundation Range Overall

This data set included products and brands known in the US and abroad such as Nigeria, Japan, and India. That being said, it is reasonable that some of these Foreign brands appeal to their consumers and make shades that make most sense to their population. Nevertheless, anti-blackness is still a prevelant issue that is worth mentioning when analyzing the ranges as a whole. 

The numbers are categorized by a lightness variable. The lighter the foundation shade is, the higher the number is because the scale goes from 1-100.

<iframe title="Foundation Shade Range of Popular Brands in the US and Abroad" aria-label="Range Plot" id="datawrapper-chart-vgXp0" src="https://datawrapper.dwcdn.net/vgXp0/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="774"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>


## Availability to US Consumers

In the following chart, we are able to see much more up close what I was mentioning about the lack of shade range especially in Indian and Japanese bestselling brands.

<iframe title="Foreign Brand Lightness Range" aria-label="chart" id="datawrapper-chart-Qmeqy" src="https://datawrapper.dwcdn.net/Qmeqy/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="440"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>


In the following chart, we begin to see a trend as to what is sold at well-known Beauty retailers. In an era of social media, online sites like Ulta or Sephora manages much of what is talked about by Beauty Gurus. Products sold at these places are more times than not considered "high end."

<iframe title="Online Brands and Other Brands Available at Ulta/Sephora" aria-label="chart" id="datawrapper-chart-BAMWH" src="https://datawrapper.dwcdn.net/BAMWH/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="440"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>


Drug Store brands are not exclusive from that of foreign or higher end brands. In the beauty community, consumers often try to find a "dupe." A "dupe" is a lesser expensive product that can has similarities to higher end products. Therefore, I found it interesting that even though not all drugstore brands are not listed in this chart, the shade range did seem hopeful.

<iframe title="Drug Store Brand Lightness Range" aria-label="chart" id="datawrapper-chart-tqlWV" src="https://datawrapper.dwcdn.net/tqlWV/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="797"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>



## So what will it be? High end or Drug Store?

Overall, this data exploration motivated me to look more into the two foundation products that are most definitely considered THE "cultural reset" of the beauty community in the 2010's.
<iframe title="Drugstore (Maybelline Fit Me) vs High End (Fenti Pro Filt'r)" aria-label="chart" id="datawrapper-chart-CUcqY" src="https://datawrapper.dwcdn.net/CUcqY/2/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="400"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>

There is no question Rihanna's work was and continues to be monumental, but here the data does not lie. It appears Maybelline decided to appeal more to darker shades, which as a drug store product is pretty hard to find. Nevertheless, the Maybelline Fit Me foundation is still not evenly distributed. Maybelline instead cut back on some of their lighter shades in order to fit 1 more Medium, Medium-Dark, and Dark shades in comparison to Fenty.


For my last question I hoped to find out if BIPOC founders were the answer to diversity and inclusion in makeup. With the exception of Maybelline, I found most drug store products did not have much shade range and as a result made me look ashy. I was also curious about how many BIPOC founders were involved in the makeup industry. Of course, this data set is limited, so I know it may not be fully representative. However, it does include some of the most popular brand names, which can be telling of what the actual set would look like. 
<iframe title="Makeup Brand Founder's Ethnic Background and Price Range (Brands available in the US)" aria-label="chart" id="datawrapper-chart-pHUi0" src="https://datawrapper.dwcdn.net/pHUi0/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="400"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>

As for my thoughts about the chart above, I know that at first glance it may seem like more BIPOC founders decide to go for the High End price range route. If I were to leave my analysis at that, however, I would fail to recognize the struggle that exists to create a brand, especially when you come from a background that is traditionally not afforded with the same economic or social opportunites and resources.

Finally, I have found this data useful to finally decide which drugstore and higher end foundations are worth a try. And eventually which foreign makeup brands to explore more. It's important that darker complexion people feel and find a variety of choices since they are too often neglected in various aspects of society. Makeup can be a source of comfort, empowerment, and creativity. I believe that no one should be neglected those opportunities.
