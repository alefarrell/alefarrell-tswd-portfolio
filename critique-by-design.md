| [home page](README.md) | [data viz examples](dataviz-examples.md) | [critique by design](critique-by-design.md) | [final project I](final-project-part-one.md) | [final project II](final-project-part-two.md) | [final project III](final-project-part-three.md) |

# Critique by Design
Understanding Global Attitudes Toward Bribery

## Step 1: The Visualization

<img width="925" height="673" alt="image" src="https://github.com/user-attachments/assets/0170f09b-a63a-4c6b-a181-9ca1366c2875" />

_Source:_ Herre, Bastian; Samborska, Veronika; Ortiz-Ospina, Esteban. “Corruption.” Our World in Data.

I selected this visualization from [Our World in Data](https://ourworldindata.org/corruption) because it offers a compelling global view of how people across different countries perceive bribery--specifically, whether they believe it’s ever justifiable.  The map, rendered in shades of green, quickly conveys cross-country differences and invites reflection on cultural attitudes toward corruption.

What caught my attention most was Mexico’s placement--lower on the acceptance scale than I expected, given how often bribery is discussed as a social issue at home.  That unexpected insight was what initially drew me in and made me want to understand how design choices could clarify or complicate that story.

## Step 2: The Critique
Overall, the visualization succeeds in providing a clear global overview and encourages quick comparison between nations.  However, several design elements make it less effective for deeper engagement.

The color scheme, for instance, uses a green gradient--an odd choice given the negative connotation of the topic.  Darker green tones unintentionally suggest something “positive” or “healthy,” which conflicts with the seriousness of bribery.  A more neutral or divergent palette (reds, oranges, or grays) might better communicate that moral tension.

I also noticed a disconnect between the map’s percentage data and the 1-10 “justifiability” scale in the original dataset.  Aligning those units would help users interpret the information more intuitively.

The primary audience seems to be Our World in Data’s general readership-- students, researchers, and journalists interested in global issues.  While the map offers a solid overview, it lacks narrative depth or interactive context that could help audiences understand why certain countries rank as they do.  Adding context, such as economic or political indicators, could turn the visualization from an observation into a story.

## Step 3: Sketch a Solution

<img width="1202" height="946" alt="image" src="https://github.com/user-attachments/assets/aa74aa45-b55e-479b-96e6-fa3d0f56babb" />

In my _QUICK_ redesign, I focused on emotional alignment and interpretive clarity.  I retitled the visualization “When Is a Bribe Ever Okay? Most Say Never.”  Highlighting never in blue helped immediately connect the moral stance to its visual representation, addressing the confusion caused by the original color scheme.

I also experimented with a more consistent, monochromatic palette and unified data units to make the visualization easier to read at a glance.

## Step 4: Test the Solution

I shared the revised concept with peers and classmates, asking broad, open-ended questions like:
- What do you think this visualization represents?
- What stands out or feels unclear?
- Who do you think this is for?
- What would you change?

Key Takeaways:
Feedback revealed that while connecting the color of never to the title improved clarity, using two contrasting colors created new confusion.  Simplifying the gradient to a single hue was suggested to improve readability.

Others recommended adding motion or narrative-- such as animating the map over time-to highlight shifting attitudes and spark curiosity.  Building on my own reaction to Mexico’s score, we discussed layering in complementary data (like reported bribery incidents) to give audiences a richer understanding of context and contradiction.

## Step 5: Building the Solution

<div class="tableauPlaceholder" id="viz1763131703789" style="position: relative;">
  <noscript>
    <a href="#">
      <img 
        alt="Quién dijo we’re corrupt? ACROSS THE AMERICAS, La Mayoría Says Bribes Are NEVER OK — Data source: Integrated Values Survey (ourworldindata.org/corruption)"
        src="https://public.tableau.com/static/images/QC/QC54GQNNQ/1_rss.png"
        style="border: none;"
      />
    </a>
  </noscript>

  <object class="tableauViz" style="display: none;">
    <param name="host_url" value="https%3A%2F%2Fpublic.tableau.com%2F" />
    <param name="embed_code_version" value="3" />
    <param name="path" value="shared/QC54GQNNQ" />
    <param name="toolbar" value="yes" />
    <param name="static_image" value="https://public.tableau.com/static/images/QC/QC54GQNNQ/1.png" />
    <param name="animate_transition" value="yes" />
    <param name="display_static_image" value="yes" />
    <param name="display_spinner" value="yes" />
    <param name="display_overlay" value="yes" />
    <param name="display_count" value="yes" />
    <param name="language" value="en-US" />
    <param name="filter" value="publish=yes" />
  </object>
</div>

<script type="text/javascript">
  var divElement = document.getElementById('viz1763131703789');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width = '100%';
  vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


Through redesign and iteration, I learned that data visualization isn’t just about accuracy--it’s about empathy and storytelling.  The process of gathering feedback was invaluable; it reminded me that effective design often comes from stepping outside my own perspective and observing how others interpret the same data.

As someone with a background in theatre and production management, this felt familiar yet distinct: where theatre builds empathy through narrative and performance, visualization does it through clarity and connection.  Inviting peers and roommates into my process helped transform static numbers into something conversational and human.

Though I wish I’d had more time to refine and animate the design, this project reinforced my belief that good visualization—like good theatre--does more than inform.  It makes people feel something, reflect, and ask new questions.

## References
Few, Stephen. “Data Visualization Effectiveness Profile.” Perceptual Edge, 2017.

Georgia State University Library, dir. Data Ready Part 6: Correlation, Causation & Misleading Data. 2021. 09:18. [https://www.youtube.com/watch?v=emb6EoIDcnw](https://www.youtube.com/watch?v=emb6EoIDcnw).

“The Best 15 Gold Green Color Palette Combinations.” Accessed November 13, 2025. [https://piktochart.com/tips/gold-green-color-palette](https://piktochart.com/tips/gold-green-color-palette).

Peck, Evan. “Data Is Personal. What We Learned from 42 Interviews in Rural America.” Multiple Views: Visualization Research Explained, May 20, 2019. [https://medium.com/multiple-views-visualization-research-explained/data-is-personal-what-we-learned-from-42-interviews-in-rural-america-93539f25836d](https://medium.com/multiple-views-visualization-research-explained/data-is-personal-what-we-learned-from-42-interviews-in-rural-america-93539f25836d).


## AI acknowledgements
OpenAI. (2025). ChatGPT [Used to check and refine spelling, grammar, and writing style].

