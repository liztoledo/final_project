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



<iframe title="Foundation Shade Range of Popular Brands in the US and Abroad" aria-label="Range Plot" id="datawrapper-chart-vgXp0" src="https://datawrapper.dwcdn.net/vgXp0/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="774"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>


## Availability to US Consumers


<iframe title="Foreign Brand Lightness Range" aria-label="chart" id="datawrapper-chart-Qmeqy" src="https://datawrapper.dwcdn.net/Qmeqy/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="440"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>


<iframe title="Online Brands and Other Brands Available at Ulta/Sephora" aria-label="chart" id="datawrapper-chart-BAMWH" src="https://datawrapper.dwcdn.net/BAMWH/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="440"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>

<iframe title="Drug Store Brand Lightness Range" aria-label="chart" id="datawrapper-chart-tqlWV" src="https://datawrapper.dwcdn.net/tqlWV/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="797"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>

## Drugstore vs High End
<iframe title="Drugstore (Maybelline Fit Me) vs High End (Fenti Pro Filt'r)" aria-label="chart" id="datawrapper-chart-CUcqY" src="https://datawrapper.dwcdn.net/CUcqY/2/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="400"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>

<iframe title="Makeup Brand Founder's Ethnic Background and Price Range (Brands available in the US)" aria-label="chart" id="datawrapper-chart-pHUi0" src="https://datawrapper.dwcdn.net/pHUi0/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="400"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>
