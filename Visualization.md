## This is the part 2 of the case study: How do geographically close zip codes impact each other?

In part1, we predicted the top 10 zip codes for property investment and we found 5 zip codes among those 10 are in Texas. So, in part 2, we choose to analyze the demographic characteristics of close zip codes in Texas. 

The software we use is Tableau. 

There are two findings:

### 1. Close zip codes tend to have similar average household size of occupied housing unit in Texas


<div class='tableauPlaceholder' id='viz1666764122143' style='position: relative'><noscript><a href='#'><img alt='Avg household size of occupied housing unit in Texas ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Av&#47;AvghouseholdsizeinTexas&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='views&#47;AvghouseholdsizeinTexas&#47;Sheet2?:language=en-US&amp;:embed=true&amp;publish=yes' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Av&#47;AvghouseholdsizeinTexas&#47;Sheet2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>  
  var divElement = document.getElementById('viz1666764122143'); 
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script'); 
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js'; 
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

The darker the color, the higher the average household size of occupied housing unit. Similar colors represent similarities in average household size. 

From the visualization, we can see close zip codes tend to have similar average household sizes. In addition, families in the south of Texas, the northwest of Texas, and downtown Texas tend to have more households in a housing unit compared with other regions in Texas. 


### 2. Close zip codes may have similar rent. 

<div class='tableauPlaceholder' id='viz1666766279577' style='position: relative'><noscript><a href='#'><img alt='Median Gross Rent in Texas ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Me&#47;MedianGrossRentinTexas&#47;Sheet3&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MedianGrossRentinTexas&#47;Sheet3' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Me&#47;MedianGrossRentinTexas&#47;Sheet3&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>
  var divElement = document.getElementById('viz1666766279577');
  var vizElement = divElement.getElementsByTagName('object')[0];  
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';  
  var scriptElement = document.createElement('script');    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js'; 
  vizElement.parentNode.insertBefore(scriptElement, vizElement);  
</script>

The darker the color, the higher the gross rent. Similar colors represent similar gross rent. 

From the visualization, we can clear clusters with darker colors, which means the rent in those regions is higher than rent in other regions. 


In addition, the development of one area might boost the development of its neighbors or impede the development of its neighbors. For future work, we can choose metrics as a proxy for "development" and create visualizations to see if there are relationships between demographic similarity and economic development. 
