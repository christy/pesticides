# Sonoma County pesticides - Graton

Visualization Tool Used: tableau public https://public.tableau.com/en-us/s/ which means all visualizations and cleaned data behind visualizations are visible to the public.

Tableau Visualizations are here:  https://public.tableau.com/profile/cbergman#!/vizhome/GratonPesticidesworkbook/Story1

The visualization below might not render interactively on this page.  To see what an interactive visualization will look like on your web page, see this sample:  https://cbergmanblog.blogspot.com/2020/02/graton-pesticides.html

<div class='tableauPlaceholder' id='viz1585257066585' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Gr&#47;GratonPesticidesworkbook&#47;Story1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GratonPesticidesworkbook&#47;Story1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Gr&#47;GratonPesticidesworkbook&#47;Story1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /></object></div>           

<br>
If you want to use these visualizations on your own web page, copy/paste this HTML embedding script:<br>

```html
<div class='tableauPlaceholder' id='viz1585257066585' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Gr&#47;GratonPesticidesworkbook&#47;Story1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GratonPesticidesworkbook&#47;Story1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Gr&#47;GratonPesticidesworkbook&#47;Story1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1585257066585');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
```

Data Notes:
Pesticide Use Report (PUR) includes fields such as: 
date products were applied, product name, Permittee name, Lot number, address, quantity used, unit quantity.  https://www.cdpr.ca.gov/docs/pur/purmain.htm
Note: CDPR county codes:  Sonoma = 49
Note: CDPR commodity codes:  Wine grape = 29143, Apple = 4001
Conversion to pounds:  gallons product used * density * specific gravity, where 
Product technical fields were taken from the CDPR product database.
