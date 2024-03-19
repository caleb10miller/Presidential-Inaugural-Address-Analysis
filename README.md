# Presidential-Inaugural-Address-Analysis

## Overview
This project explores the evolution of language in U.S. presidential inaugural addresses over time, offering insights into changing political rhetoric, national priorities, and the relationship between presidents and the public. By analyzing speeches from the country's inception to the present day, we uncover linguistic trends and patterns that reflect broader societal and geopolitical shifts.

## Team Members
- Caleb Miller
- Luke Chesley
- Harrison Pauwels

## Dataset
Our dataset comprises inaugural addresses sourced from The American Presidency Project at UC Santa Barbara. Through web scraping techniques, we collected the text of each speech, which was then cleaned and processed for analysis.

## Methodology
- **Data Acquisition and Preprocessing**: Python, with the Requests and BeautifulSoup modules, was used to scrape and parse the inaugural addresses. The raw text data was cleaned to remove non-text characters like newline and tab characters.
- **Analysis**: The analysis involved both simple string manipulation and advanced natural language processing techniques. Tools like NLTK were employed to examine word frequency, sentence length, parts of speech, and the Flesch-Kincaid readability scores of the addresses.
- **Visualization and Dashboard Creation**: Using Plotly for graph creation and Dash for dashboard implementation, we built interactive visualizations to allow users to explore the data. Our dashboard enables filtering by president and year for customized analysis.

## Key Findings
- A shift towards simpler, more accessible language in recent speeches.
- A consistent trend in speech length, with modern addresses being shorter.
- An increase in the use of comparative adjectives, reflecting a focus on achievements and goals.
- The evolution of language mirrors changing societal values and technological advancements.

## Limitations
The study focuses solely on inaugural addresses, which may not fully represent the broader historical and political context. Additionally, the inherent limitations of the dataset, including its size and frequency, may impact the interpretation of long-term trends.

## Future Work
Future research could extend this analysis to include sentiment analysis, compare speeches of global leaders for a cross-cultural perspective, or incorporate speech delivery elements like tone and pacing. Expanding the dataset and employing more advanced analytical techniques could offer deeper insights into political communication strategies.

## Conclusion
This project highlights the dynamic nature of presidential rhetoric and its reflection of historical and cultural shifts. By leveraging modern data analysis tools, we gain a deeper understanding of how U.S. presidents have communicated with their constituents and the world.

## References
The American Presidency Project, UC Santa Barbara: https://www.presidency.ucsb.edu/
