1. What is the problem you are solving?
> Businesses or your audience care about problems. Make the problem clear and relatable

Every year, thousands of gender-based violence cases in Kenya go unrecorded by official systems. When a survivor reports to an NGO or visits a hospital but never files a police report, that case becomes invisible to the government. The result is that policymakers and resource allocators are making decisions based on incomplete data and thus, funding goes where the numbers point, not where the need actually is. The real problem isn't just violence. It's that the violence we can't count is the violence we can't respond to.

2. What tools did you use?
> Python? GeoPanadas? Google Big Query?
> Tell your audience how you got the answer,  tools show your capability
> Dive deep in this in your technical  article

This project uses Python as the primary language, with pandas for cleaning and merging datasets from three different sources — the Kenya Demographic and Health Survey (KDHS 2022), Kenya National Police Service annual crime reports, and NGO situation reports. GeoPandas is used to match that data to Kenya's 47 counties and render it as a choropleth map. Plotly makes that map interactive. The most honest tool in the project is a spreadsheet because some of the police data lives in PDFs and has to be extracted by hand, which is itself a finding worth writing about.

3. What insights did you or do you want to discover?/ What Solutions do you want to offer? Do People even need these solutions?
> Don’t just say “dashboard done.”
> Share the “aha!” moments, they matter more that the visuals

The central question is: which counties have the largest gap between officially reported GBV cases and what NGOs are documenting on the ground? The "aha" moment isn't a number — it's a map. When you see certain counties lit up in deep red because their NGO-to-police reporting ratio is 6:1 or 8:1, you're not looking at a data visualization. You're looking at a geography of silence. The insight is that underreporting is not random, it clusters. Certain regions are systematically undercounted, and that pattern likely correlates with access to police stations, cultural barriers to reporting, and the density of NGO presence. That's the story the data tells that no single report has shown visually before.

4. How would a business or a community (for Social Impact Projects) benefit from your work?
> Be specific. Think money saved, process improves, better decisions made
> That’s your **real value**

An NGO deciding where to open a new safe house or deploy mobile legal aid units currently has to rely on instinct or whichever county shows up most in the news. This project gives them a county-level underreporting map they can use to make that decision with evidence. The benefit is specific: fewer resources wasted on already-served areas, more support reaching counties where survivors have no formal channel to report to. For county governments, the map is an accountability tool that works as a visual argument for why certain areas need more police gender desks or better coordination with civil society. The real value is turning a data gap into a decision-making tool.