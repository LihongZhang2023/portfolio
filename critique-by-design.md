 | [home page](https://lihongzhang2023.github.io/portfolio/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique by Design
<div class='tableauPlaceholder' id='viz1699835584215' style='position: relative'><noscript><a href='#'><img alt='Top  Tomato &amp; Potato  Producers in 2021 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;To&#47;TopTomatoPotatoProducersin2021&#47;TopProducer&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='TopTomatoPotatoProducersin2021&#47;TopProducer' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;To&#47;TopTomatoPotatoProducersin2021&#47;TopProducer&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1699835584215');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>Text here...    

### Reflection    
Link to the original visualization:  [2023/W17: Biggest Tomato & Potato Producers](https://data.world/makeovermonday/2023w17) 
   
While I went through several visulizations on the MakeOverMOnday website, the Tomato/potato Producer visualization caught my eyes. Besides tamotas are my favorite vegitables, I know there are a lot to look into for improvement.

At 1st glance, it's a very colorful viz. However, there are too many colors competing for attention which makes it hard to tell what is the main focus. The large font for the title works well, so I figure out immediately the viz is showing top tomato producers (not Potato). The drawback of the viz is that there are too much distraction. For instance, too many colors used for the bars (countries). The tomato background is distracting, adding more unnecessary colors to the already too busy viz. Moreover, the donut chart with year on lower right is confusing, it took me a while to figure out that it works as a filter for Year. The design is creative however unnecessary. It misleads audience to pay more attention to the filter than the graph itself. 

With the above thought in mind, my 1st step is to sketch another version of bar chart. I eliminated the subtitle and indicated the Value Weight by Ton as the title of x-axis. Logos of the countries is duplicate information with the country names, it needs to be removed. I also changed the format of values with measure of thousand to make it easier for audience's eyes, and align them all on the right next to the bars. As a solution for overused colors, I used single hue of orange color and gradient saturation for different scale of values/bars. I drafted a visulization in Tableau as below:  
![Image](image001.png)

My next step is to obtain feedback from others for improvement. I emailed a questionaire with my viz draft to one of my colleagues and a friend, and received prompt responses.  

#### Feedback 1 (provided by a General Manager of a corporation, 48 years old)   
Q1. Can you tell me what you think this is?   
A:  Chart of value of exported tomatoes from various countries  
Q2. Can you describe to me what this is telling you?  
A: That China exports the most, by a large margin of more than 3x the next largest exporter  
Q3. Is there anything you find surprising or confusing?  
A: I am not sure if this is the just $ value size of tomato industry in the country, or the $value of exports—the “value” is not defined in any specific term.  
Q4. Who do you think is the intended audience for this?  
A: Economic conference, or readers of government report.  
Q5. Is there anything you would change or do differently?  
A:  Clarify what the value represents—export, industry revenues, etc. it is not clear.  
Q6. Is there any other information you would like to know but you couldn't find from the graph?   
A: What is the unit of measure for dollars?  Is it bushels of tomatoes, or gross sales on some kind of international tomato market?   

#### Feedback 2 (provided by a colleague at the university, 55 years old)   
Q1. Can you tell me what you think this is?  
A:  A research on crops produced worldwide.  
Q2. Can you describe to me what this is telling you?  
A: China, India and Turkey are the top three tomato producers.  
Q3. Is there anything you find surprising or confusing?
A: What do the numbers stand for, sum of sales?  
Q4. Who do you think is the intended audience for this?
A: General public  
Q5. Is there anything you would change or do differently?  
A:  Clarify the values  
Q6. Is there any other information you would like to know but you couldn't find from the graph?  
A: I'm curious about the ranking in other years.

Based on the feedback, I realized the values have been mislabeled as currency, and the title for x-axis was hidden which caused confusion. The feedback also suggests that besides the ranking of tomato in 2021, audience may also be interested to know some related information such as rankings in different years or different crops. The bar chart works effectively for conveying a clear idea as it's supposed to. Therefore I kept the bar chart. In addition, I enabled the filters for Year and Item type so that more information will be available for audience via a simple bar chart. The final version of the visualization displays a list of top tomato or Potato producers. A slide bar "Top Producer" created by Parameter and Set enables viewers to select how many top producers they would like to see.
