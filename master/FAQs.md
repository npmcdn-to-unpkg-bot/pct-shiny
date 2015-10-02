---
title: "FAQs File"
author: "AA"
date: "Wednesday, September 30th, 2015"
output: html_document
---
<html>
<script>
function toggleElement(id) { 
  if(document.getElementById(id).style.display == 'none') 
  { 
    document.getElementById(id).style.display = ''; } 
  
  else { 
    document.getElementById(id).style.display = 'none'; 
    } 
  }
  
</script>
<b> Under development </b>

[1\. Does hilliness matter for cycling? Do the Dutch just cycle more because the Netherlands is flatter?](javascript:toggleElement('a1'))

<div id="a1" style="display:none">Hilliness is certainly an important predictor of cycling levels in England, with the probability of cycling a trip falling steadily as the hilliness of the local area increases (Figure 1). Overall, people in the tenth of the population in the flattest areas are three times more likely to cycle a trip than the tenth of people in the hilliest areas (2.8% trips cycled vs 0.8%).  

![Figure 1: Proportion of trips cycled in England, according to the hilliness of the local area](./assets/Figure 1_FAQs.jpg)

It is also true that the Netherlands is a flatter country than England. As illustrated in Figure 2, around 80% of people in the Netherlands live in areas that are below the 20th centile for local hilliness in England. Under 4% of people in the Netherlands in live in areas that are above the 50th centile for hilliness in England. Note that in both England and the Netherlands the local area is defined using administrative areas desgined to contain populations of around 1500 individuals.  
Figure 2: Distribution of the population of the Netherlands in tersm of the hililness of their local area, relative to the tenths defined in England.  
We estimated what would happen if to cycling levels in England if England had the same flat topography as the Netherlands (but the existing infrastructure, travel patterns and cycling cultures). We did this by re-weighting the cycle mode share shown in Figure 1 according to the Dutch distribution of hilliness shown in Figure 2 – i.e. giving much more weight to the cycling levels of those living in the flattest parts of England than those living in the hilliest parts. In this ‘Dutch levels of hilliness’ scenario, the proportion of trips cycled in England rose from 1.7% to 2.6%. This is still ten times lower than the mode share of 26.7% actually observed in the Netherlands. So although hilliness does explain a small part of why the English cycle less than the Dutch, it still leaves a massive difference unexplained. Or to put it another way, only if cycling levels in England were increased ten-fold would ‘the Netherlands is flatter’ become a convincing excuse for England lagging behind.  
</div>

[2\. How does propensity to cycle differ between London and the Netherlands?](javascript:toggleElement('a2'))

<div id="a2" style="display:none">People in the Netherlands make 26.7% of trips by bicycle, fifteen times higher than the figure of 1.7% in England. In addition, cycling in England is slewed towards younger, male cyclists (Figure 1A). By contrast in the Netherlands cycling remains common into older age, and women are in fact slightly more likely to cycle than men (Figure 1B). This means that the difference between England and the Netherlands is particularly large for women and older people (Figure 2). For example, whereas the cycle mode share is ‘only’ six times higher in the Netherlands than in England for men in their thirties, it is over 20 times higher for women in their thirties or men in their seventies and eighties. For women in their seventies and eighties, the cycle mode share is over 60 times higher in the Netherlands than in England.  
Figure 1: Proportion of trips cycled in England and the Netherlands, stratified by age and sex  
Figure 2: Ratio of cycle mode share in the Netherlands versus England, stratified by age and sex  
In both countries, the probability of cycling falls rapidly as trip distance increases. Interestingly, the shape of this ‘distance decay’ relationship is generally similar between the two countries (Figure 3). In other words, the Dutch achieve their higher cycling levels by boosting the relative probability that trips of all distances will be made by bicycle. This indicates that the potential to increase cycling levels in England exists for longer trips (≥10km) as well as for the shorter trips that are more often targeted in cycling interventions, perhaps through improved infrastructure or a more widespread adoption of ebikes. The only noticeable difference between England and the Netherlands is that the Dutch are relatively more likely to cycle short trips ≤1.5 miles than the English. Plausibly, this reflects being cycled in the Netherlands that are more often walked in England.  
Figure 3: ‘Distance decay’ curves in England and the Netherlands, showing the probability that a trip of a given distance will be cycled relative to a trip of 2 miles  
</div>
</html>