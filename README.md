# Sleep-Disorder-Analysis
In this project, I investigated sleep quality metrics associated with sleep disorders, using Python for EDA and Tableau for a dashboard. I also implemented a machine learning pipeline with Scikit-Learn to streamline standard scaling and logistic regression. Later, I employed cross-validation strategies to fine-tune predictive performance with various models including random forest and SVC.

## Univariate Analysis
Distribution of sleep disorders

![download](https://github.com/milliehuang2022/Sleep-Quality/assets/87724542/9c4a5b8b-e454-4fb3-a319-5e37165273e4)

Distribution of sleep disorders by gender

![download](https://github.com/milliehuang2022/Sleep-Quality/assets/87724542/c7df251e-4b3c-4ba8-af41-a9bc54b0db42)

Density of Quality of Sleep by Sleep Disorder

![download](https://github.com/milliehuang2022/Sleep-Quality/assets/87724542/d78dbf87-c69d-475a-a0a0-e2a755c027e5)

Density of Sleep Duration by Sleep Disorder

![download](https://github.com/milliehuang2022/Sleep-Quality/assets/87724542/29f27af2-b4d6-4d36-8d3b-b131548e4913)

Density of Stress Level by Sleep Disorder

![download](https://github.com/milliehuang2022/Sleep-Quality/assets/87724542/4effc0c2-146f-467f-8e25-e3dfe20f28c4)

## Multivariate Analysis

Joint plot analyzing the relationship between Quality of Sleep and Sleep Duration 

![download](https://github.com/milliehuang2022/Sleep-Quality/assets/87724542/f5868ecf-def5-468e-8016-c8d6db9b527a)

Linear regression plots analyzing the relationship between Sleep Duration, Physical Activity Level, Stress Level, Heart Rate, and Daily Steps with Quality of Sleep, faceted by Sleep Disorder

![download](https://github.com/milliehuang2022/Sleep-Quality/assets/87724542/45751d6d-5bdc-476a-93e4-ef7c71fba84e)

Analyzing Quality of Sleep in Relation to Sleep Duration, Faceted by Sleep Disorder

![download](https://github.com/milliehuang2022/Sleep-Quality/assets/87724542/096b4032-0656-4758-ba76-71622a5c01b9)

Heatmap of Correlation Between Numeric Variables

![download](https://github.com/milliehuang2022/Sleep-Quality/assets/87724542/dc71ad33-a1e7-4361-8646-ccecdd190113)

## Tableau Dashboard

To summarize my findings in a cohesive visualization, I created a Tableau dashboard with easily accessible results, in which different sleep disorders can be highlighted for clarity.

<div class='tableauPlaceholder' id='viz1704094212920' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Sl&#47;SleepAnalysis_17040942051890&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='SleepAnalysis_17040942051890&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Sl&#47;SleepAnalysis_17040942051890&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1704094212920');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.minWidth='420px';vizElement.style.maxWidth='650px';vizElement.style.width='100%';vizElement.style.minHeight='587px';vizElement.style.maxHeight='887px';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.minWidth='420px';vizElement.style.maxWidth='650px';vizElement.style.width='100%';vizElement.style.minHeight='587px';vizElement.style.maxHeight='887px';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='1377px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

## Building a Model + Pipeline

![download](https://github.com/milliehuang2022/Sleep-Quality/assets/87724542/12a33156-f092-4ae5-8d23-d0dd48c23f31)

![download](https://github.com/milliehuang2022/Sleep-Quality/assets/87724542/3d03c649-6d44-45c1-8768-79c3715a3ad9)
