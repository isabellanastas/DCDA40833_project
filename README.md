# The Look of Health - Website File Structure

## Project Pages Created

Your research project website now has the following structure:

### Main Pages
1. **index.html** - Home/Landing Page
   - Hero section with project title and description
   - Project intro section
   - Featured themes (4 cards)
   - Key findings section
   - Navigation to all other pages

2. **proposal.html** - Project Proposal
   - Research question
   - Project objectives
   - Research scope
   - Methodology
   - Key variables & themes
   - Significance & impact
   - Timeline & milestones
   - Limitations & considerations

3. **bibliography.html** - Annotated Bibliography
   - Overview of sources
   - 5 thematic categories for sources:
     - Visual Culture & Aesthetics
     - Social Media & Digital Culture
     - Health Communication & Wellness Culture
     - Influencer Culture & Personal Branding
     - Media Literacy & Critical Analysis
   - Space to add 15+ annotated sources

4. **survey.html** - Survey Results
   - Survey methodology
   - Survey overview
   - 4 data visualization placeholders
   - Key survey insights
   - Notable respondent quotes
   - Statistical analysis section
   - Survey limitations

5. **case-studies.html** - Social Media Case Studies
   - Overview section
   - 4 detailed case study cards with:
     - Platform, date, and focus information
     - Analysis section
     - Screenshot/example placeholders
   - Comparative analysis
   - Broader trends & patterns
   - Content analysis framework

6. **insights.html** - Final Insights
   - Executive summary
   - Key findings
   - Main conclusions
   - Answering the research question
   - Implications & applications (for multiple audiences)
   - Limitations of the research
   - Future research directions
   - Reflection on research process
   - Final thoughts

### Styling
- **styles.css** - All CSS styling for the entire website
  - Responsive design (desktop, tablet, mobile)
  - Modern color palette
  - Typography and spacing
  - Navigation styling
  - Content card layouts
  - Bibliography and case study specific styles

## How to Customize

1. **Text Content**: Replace all bracketed placeholders like [Add Title Here] with your own content

2. **Images & Visualizations**: 
   - Add chart images to the [INSERT CHART HERE] placeholders
   - Add screenshots to [INSERT SCREENSHOTS OR EXAMPLES HERE]
   - Store images in the `/images` folder

3. **Navigation**: The navigation menu at the top of each page automatically links all pages together

4. **Metadata**: Update footer information on each page:
   - Course name and number
   - Instructor name
   - Your university/institution
   - Your name(s)
   - Your email

5. **Colors & Styling**: Edit variables in styles.css at the top of the file under `:root`

## File Links

- Home: index.html
- Project Proposal: proposal.html
- Annotated Bibliography: bibliography.html
- Survey Results: survey.html
- Social Media Case Studies: case-studies.html
- Final Insights: insights.html

All pages share:
- Same navigation menu
- Same styling (styles.css)
- Responsive mobile menu
- Professional footer

## Tips for Using the Site

- Each page has clear section headers showing where to add content
- Look for comments like "ADD YOUR..." or "[Insert content here]"
- Use the research-list class for bullet points
- The visualization-placeholder class is for charts/graphs
- The case-study-media class is for screenshots
- The content-card class provides consistent card styling

Good luck with your research project!
