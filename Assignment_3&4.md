# Critique By Redesign    
## The Original Visualization    
Original Visualization: [The Living Wage Gap](https://www.statista.com/chart/25574/living-wage-vs-minimum-wage-by-us-state/)    
I chose this visualization because I thought it was rather middle-of-the-road in terms of quality (neither the worst I've seen nor the greatest), so it had potential for improvement, and it met the requirements of the assignment. I haven't found any critiques of this visualization, the data cited is still publicly available (found [here](https://livingwage.mit.edu)) and the visualization itself is still publicly available. I didn't think the visualization was beyond redemption or the worst I've ever seen, but I didn't think it was the greatest either. Some glaring improvements needed to be made, but there were some good foundational pieces.

Although I find myself rather neutral when it comes to a debate over the minimum wage, I thought the data were interesting and was curious to see if I could find any regional patterns. I believe I did, which makes the project somewhat rewarding for me, personally. Although I did not include this in my final visualization  as I thought it would be a little overwhelming, I found it interesting to see how which states were "bad" and "good" shifted slightly when I switched from dollar amounts to percentatges.    

## My Journey    
I wasn't sure whether Tableau or Flourish would be my prefered tool for making this visualization, so I started with both. After some time working in Flourish, I ran into some difficulty getting particulars of the data to render as I preferred, so I switched to Tableau. Tableau rendered these things the way I envisioned, so that was my tool for the rest of the project.



For the initial notebook sketch, it was very much so a "sketch". I picked one color and then labeled which states got which shades... which I altered for my final product. I received constructive criticism from two classmates, who made some of the following suggestions (paraphrased):   
- Including the number with each state was a good way to highlight state differences
- The color choice will matter a lot
- The title was invaluable
- Including a source on what "living wage" means would be valuable
- Including a caption or paragraph on what a "living wage" is would be valuable
  - We further discussed the source and chose the critical section of text to include in this paragraph or caption
- Updating the data to the current year is a good idea
- Neither student felt strongly about listing the percentage or the literaly dollar difference

I was pleased to see that including a number with each state was important (an aspect of the original design I intended to keep), but I was a little disappointed that no one seemed to care about the percentage vs. number conundrum. I decided that I felt a percentage told a more complete story, so I elected to stick with that idea. Although I changed the title slightly for my final rendition, I decided to keep it as similar as I could, since both classmates noted its value. I decided it would be essential to provide a little bit of context concerning what a "living wage" is, since that is't necessarily intuitive to most people. I pulled up the source's source's explanation and showed the most critical paragraph. My classmates agreed that probably just that section would be sufficient, as any more might run the risk of boring the reader.

### My Sketch:
![Initial Draft](/Sketch.png)

### The Critique

While I intuitively knew what I wanted my final product to look like, working through the critique exercise helped me articulate why. I considered the original visualization rather mediocre, but the scaling system forced me to quanitfy why I did. Here's what I wrote about my initial observations:
>It kind of reminds me of those round stickers people use at garage sales and such. It was kind of challenging to locate some of the states (NC, for instance). The color scheme indicated a state of alarm. If the call to action is to demand an increase in the minimum wage, these colors were effective. The first time I looked at it, I got so distracted trying to make sense of the map I lost track of what the dollars were measuring. The elements were all present, but I didn't have a great time following them during my first viewing. I was also mildly annoyed that ONLY the gap was mapped and I, as a reader, had no way of seeing what the living wage or the minimum wage actually was for each state.

Concerning the target audience, these were my thoughts:
> Americans. I think it's marginally effective. Americans like finding their state on a map (at least according to some of the class readings), but this visualization makes some of the states hard to find. The color scheme will signal to Americans that the minimum wage is too low when it is far below the cost of living, and if that was the author's intention, then it was well executed.

I continued with what I thought I'd like to alter:
> I'd like to change the map to make it actual states and alter the color scheme to be less obnoxious. Keeping the map makes it interesting and lets a reader draw conclusions about different regions of the country, rather than only individual states. Relating to the color scheme, the author does not provide any analysis as to whether the cost of living increases when minimum wage is increased and if there is an "ideal gap" between a living wage and minimum wage. Instead, the colors feed the reader the conclusion that any gap is bad, and a big gap is worse. Also, since the cost of living and therefore the value of a dollar varies state-to-state, I don't think that measuring the gap in raw dollar amounts is the best way to communicate this gap. I'd like to use percentages instead. Finally, the original visualization was from 2021. I'm going to use current data from the same source.


I didn't love the new critique method, but I didn't think it was terrible, either. It felt a little spaghetti-like to me, but perhaps I'm just not accustomed to it.

### Continuing the Process
I pretty much stuck with my initial resolutions. The only real addition to the end state was the information that displays in the Tooltip over each state. I also changed the colors... multiple times. Although I knew I didn't really like the red-yellow-orange scheme and found it too jolting, it took me a while to decide on what scheme I *did* like. I elected for a color that was cooler, but not as cold as blue or as positive as green. I didn't want to suggest that a large gap is a good thing with green or blue shades, but I'm not an activist trying to lobby for an increase in the minimum wage, either, so I didn't want to use alarmist colors. I thought a purple scale would be a neutral scheme in terms of sending a message. I still used darker colors to indicate a more concerning large gap and lighter colors to indicate a less concerning small gap. I decided that I didn't want a knee-jerk call-to-action the way the original author did, but instead preferred a more collected and thoughtful call-to-action. I wanted readers to think about the gap that exists without immediately feeling stressed. I also wanted readers to be able to focus on noticing patterns (such as the dark area in the southeast) rather than being distracted by bright colors. Overall, I'm pleased with the result.

Getting the states to be labeled in such a way that each one had a label without the labels running over each other was a challenge. I ended up using annotations for most of the smaller states and disabling their auto-labeling. This prevented smaller states from auto-rendering labels that ran over their borders, but still allowed readers to see their "big" statistic at a glance. Hovering over each state showed more data, if a reader decided they were interested. I found this interactive method to provide the best of both worlds, as the map is not too data-heavy at a glance, but further information is just a mouse movement away from a curious reader.

## End Result
I explored and looked up a lot of Tableau functionality to get my map formatted the way I wanted. I didn't realize that publishing would change how the map rendered with regard to the labels and annotations I added (the colors also shifted a bit and the state borders roughly doubled in thickness). Sharing the embedded code also changed some of the layout, which made it very frustrating to get a good final version. Truly, it felt rather like guesswork, since I had to edit in Desktop, publish, then check the rendering in my GitHub public page before I could see if a change had the effect I wanted.
What I thought my pubilcation would look like:

![In Tableau Desktop](/Target.png)

I feel that the final version on the desktop was less crowded and more legible than what I ended up with after publishing, which is rather unfortunate. Here's the final rendition:

<div class='tableauPlaceholder' id='viz1695266829083' style='position: relative'><noscript><a href='#'><img alt='Minimum Wage as a Percentage of &quot;Living Wage&quot;Single Adults, No Children ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment34_16952631849160&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Assignment34_16952631849160&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment34_16952631849160&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object>
</div>
<script type='text/javascript'>
 var divElement = document.getElementById('viz1695266829083');
 var vizElement = divElement.getElementsByTagName('object')[0]; 
 if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';}
 else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';}
 else { vizElement.style.width='100%';vizElement.style.height='777px';}  
 var scriptElement = document.createElement('script');   
 scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
 vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


Note that I included an additional source for further study in the caption for an [Explanation of Living Wage](https://livingwage.mit.edu/resources/Living-Wage-Users-Guide-Technical-Documentation-2023-02-01.pdf). As a summary, living wage is an estimate of the cost of living in a particular area. It accounts for more than what the poverty wage (which is the same across the entire continental US) accounts for. It accounts for the cost of what we consider basic needs in America and calculates the hourly wage that would be needed to meet these needs.

#### Link
Link to this page's URL: [Assignment 3 & 4](https://abiabrown.github.io/TSWD/Assignment_3&4)   
Back to main: [Home](https://abiabrown.github.io/TSWD)
