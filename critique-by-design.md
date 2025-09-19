| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Assignment Writeup: Redesigning a Data Visualization

*This document serves as a step-by-step journal of my process, reflecting on critiques, sketches, redesign choices, and the final visualization. The tone is reflective, highlighting what I learned at each stage.*


## Step 1 — The Visualization

**Original Visualization:**  
Tableau Public Link - [https://public.tableau.com/shared/Y86WFJPT3?:display_count=n&:origin=viz_share_link](#) 

<div class='tableauPlaceholder' id='viz1758245467775' style='position: relative'><noscript><a href='#'><img alt='Are LLM models performing better over time and with more parameters? Since 2023, most companies&#39; models have surpassed the 70 MMLU threshold, with 2024–25 marking a surge in both scale and benchmark score (Mmlu)[size of bubble = Parameters (Bn)]  | Filt ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;RX&#47;RXPF8JRZR&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;RXPF8JRZR' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;RX&#47;RXPF8JRZR&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' /></object></div>             
<script type='text/javascript'>                   
  var divElement = document.getElementById('viz1758245467775');               
  var vizElement = divElement.getElementsByTagName('object')[0];               
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';          
  var scriptElement = document.createElement('script');                 
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);           
</script>


**Screenshots**  
Google-
<img width="1001" height="615" alt="image" src="https://github.com/user-attachments/assets/e5d9425c-884e-4c95-a7a8-233a9024bb07" />

Chinese-
<img width="1247" height="582" alt="image" src="https://github.com/user-attachments/assets/113446cf-8327-4185-af15-cd8e1e309663" />

Mistral-
<img width="1258" height="587" alt="image" src="https://github.com/user-attachments/assets/c111da24-7f7c-4ed2-9f0f-c2bd4c9d56ed" />

Meta-
<img width="1229" height="584" alt="image" src="https://github.com/user-attachments/assets/78701517-699b-4ad1-9295-fabd0416c04f" />

**Why I Selected It:**  
I chose this visualization because it highlights an area where the representation of information could be improved. While the data is valuable, I noticed challenges in how it was being presented (e.g., clutter, lack of clarity, limited interactivity). The visualization had potential but didn’t fully communicate insights effectively to the intended audience.  

This selection also gave me an opportunity to apply critique techniques we practiced in class. Through initial critique, I quickly noticed that some encoding choices (color, size, axis scales) made the chart harder to interpret than it should be. These first impressions guided my decision to use this visualization as a basis for redesign.

---

## Step 2 — Critique & Insights

In this stage, I applied the critique method to analyze the visualization.  
Some insights I gained:  
- *Strengths:* What the visualization does well (e.g., interesting dataset, unique perspective).  
- *Weaknesses:* What was confusing or misleading (e.g., poor axis scaling, unclear labels, inconsistent legend use).  
- *Opportunities:* Ideas for redesign to improve clarity, accessibility, and storytelling.

The critique process made me think more about **who the visualization is for** and **what the audience should take away**. Instead of just re-creating the chart, I wanted my redesign to highlight trends and comparisons that were hidden in the original.

---

## Step 3 — Moving to Sketches

I began by sketching out alternative layouts on paper.  

During sketching, I realized that changing the chart type (e.g., moving from a static bar chart to a scatter or line chart) could better reveal the relationships in the data.

## Step 4 — User Feedback

I then shared my sketches with peers to gather feedback.  
Key takeaways from feedback:  
- Some sketches added clarity but introduced too many elements at once.  
- Others simplified the view too much, hiding useful detail.  
- Feedback emphasized the need for **balance** between readability and detail.  

Based on this feedback, I refined my redesign plan to focus on fewer but more effective visual encodings, such as consistent color schemes and clearer labeling.

---

## Step 5 — Redesign Implementation

With feedback in mind, I created the redesigned visualization.  


**Changes made based on feedback:**  
- Simplified the color scheme for clarity.  
- Adjusted axis scales to improve readability.  
- Reduced clutter by removing unnecessary gridlines and labels.  
- Improved tooltip design for interactivity.  

---

## Step 6 — Reflections on the Redesign

The redesigned visualization tells a more focused story:  
- It highlights the most important trends or comparisons.  
- It makes use of interactive features (filters, tooltips, highlights) where appropriate.  
- It avoids overwhelming the viewer while still providing depth.  

By moving through critique → sketches → feedback → redesign, I learned how important iteration is in visualization design. Each step revealed new opportunities to improve clarity and usability.  

---

## References
Original Data Viz source - https://informationisbeautiful.net/visualizations/the-rise-of-generative-ai-large-language-models-llms-like-chatgpt/ 
Original Dataset - https://docs.google.com/spreadsheets/u/1/d/14KzlcYOK6Xj-_6N19T2Iqro4sGaAUOLD2FovSXyefUQ/edit?gid=426115144#gid=426115144 

I used AI assistance (ChatGPT) to help structure my assignment writeup and plan my Tableau dashboard workflow. Specifically:  

- **Guidance:** AI provided suggestions on which chart types would best highlight my dataset (scatter plot, bar chart, timeline, box plot) and how to link them together with a global filter.  
- **Documentation:** AI generated a draft Markdown template to document my process, including placeholders for sketches, screenshots, and reflections.  
- **Clarity:** AI helped me refine my explanations so that the steps of critique, sketching, user feedback, and redesign were clearly articulated.  

