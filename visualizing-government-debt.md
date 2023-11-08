| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Part 1: Working with web-based visualization tools and data
Source: [Government debt data from OECD](https://data.oecd.org/chart/7faw)

Embed Code:
<iframe src="https://data.oecd.org/chart/7fb2" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7fb2" target="_blank">OECD Chart: General government debt, Total, % of GDP, 2022 or latest available</a></iframe>


# Part 2: Working with Tableau
My Tableau Public: [Highlight Table](https://public.tableau.com/views/GovernmentDebtDatahighlighttablefromOECD/highlight_table?:language=en-US&:display_count=n&:origin=viz_share_link)

Here is an example:

<div class='tableauPlaceholder' id='viz1699412464884' style='position: relative'><noscript><a href='#'><img alt='Government Debt Data(highlight table) from OECDsource: https:&#47;&#47;data.oecd.org&#47;gga&#47;general-government-debt.htm ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebtDatahighlighttablefromOECD&#47;highlight_table&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GovernmentDebtDatahighlighttablefromOECD&#47;highlight_table' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebtDatahighlighttablefromOECD&#47;highlight_table&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>      

<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1699412464884');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

# Part 3: Create your own visualization

My Tableau Public: [Tree Map](https://public.tableau.com/views/GovernmentDebtDatatree_map/tree_maps?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
<div class='tableauPlaceholder' id='viz1699418091493' style='position: relative'><noscript><a href='#'><img alt='Comparing Government Debt Data among Different Countries from 1995 to 2022source: https:&#47;&#47;data.oecd.org&#47;gga&#47;general-government-debt.htm ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebtDatatree_map&#47;tree_maps&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GovernmentDebtDatatree_map&#47;tree_maps' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebtDatatree_map&#47;tree_maps&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                


code:
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1699418091493');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

I've chosen the treemap visualization for several reasons. One notable advantage is that it allows countries with high percentages to stand out. The map is ranked from the upper left to the lower right, making it easier for the audience to identify the top-performing countries. Additionally, I've set 100% as the center value, which results in values higher than 100% being displayed in red while the rest are shown in blue. This color scheme helps draw the audience's attention to the top countries with values exceeding 100%.

Within each treemap box, all the years for each country are efficiently represented. I've also designed the labels to show the most recent data, although there seems to be an issue with them not displaying correctly. However, they work as intended in "presentation mode."

Another advantage of the treemap is that it uses color to represent values without cluttering the chart with all the numerical data. This approach reduces visual noise while still clearly conveying the value relationships. Moreover, in the treemap, each country is shown as a rectangle, which I believe is more convenient for the audience to read compared to a long list in a table. The size of each rectangle corresponds to the value it represents, providing a visual representation of the data.
