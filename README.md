# MSDS-436

## Recommendation for Management
The short answer is yes, there are significant opportunities for automating financial services using conversational assistants and AI agents. The Gartner report points out that companies are currently using AI in three ways: to augment productivity, entirely behind-the-scenes, and across the board including customer-facing use-cases. The Gartner report also considers feasability in terms of three components: technical feasibility, internal readiness, and external readiness. Based on these three factors, various AI technologies can be assessed as low, medium, or high feasability. Looking at Banking specifically, Gartner highlights Frontline AI co-pilots, Banking fraud prevention, and synthetic credit data as high feasability use cases for AI that span the range from customer-facing to entirely behind-the-scenes. The cool part about this is financial services are able to use AI to both automate mundane tasks *and* innovate. Loan processing, for example, is categorized at medium feasability, mostly internal, and potentially game-changing. There are absolutlely multiple AI technologies available at various risk levels and customer-facing roles depending on what a particular financial instution is interested in.

Summary from ChatGPT itself: 
> AI adoption in financial services is no longer experimental—it's integral to the competitive strategies of major players and startups alike. Firms that leverage AI for automation, personalization, and risk management are seeing substantial operational efficiencies and customer satisfaction improvements. The scale of adoption is expected to grow further as technology advances and regulations adapt to these innovations.


## Repository Folders and Files
1. "Code" Folder contains files used to get Scrapy working
 * The "quotes_spider.py" file is the one that works and outputs "quotes.jsonl"
 * There are additional screenshots from troubleshooting in this folder
2. The "Research" Folder contains resources found while researching
 * Saved ChatGPT conversations
 * PDFs of the cited textbook chapters
 * A really useful report by Gartner "Map Your AI Use Cases by Opportunity: Ready The IT Team to Drive Success", as well as an image from the report ("the-ai-opportunity-radar.png")
 
## Approach to using Generative AI
After reading the Gartner report, I asked ChatGPT some of the relevant research questions. I found that ChatGPT's information corroborated both the Gartner report and my own lived experience (e.g. interacting with Bank of America's Erica Personal Assistant). Not having a strong financial background myself, ChatGPT was able to fill in knowledge gaps and further contextualize the benefits of GenAI technologies in that space.


## Additional Notes for Myself
### Gartner Wikipedia Article Summary:
* Gartner is a tech research and consulting firm
* Based in Connecticut
* Shares research through private consulting, executive programs, and conferences
* Clients are large corporations, government agencies, technology companies, and investment firms
* Founded in 1979
* Has acquired other companies


What Does Gartner have to say about AI and conversational assistants?
-> See Gartner’s exec’s guide


### Forrester Research Wikipedia Article Summary:
* Forrester is a research and advisory company offering a variety of services including research, consulting, and events
* Headquarters in Cambridge, MA and London with additional offices around the world
* Founded in 1983


### Scrapy Resources: 
* https://scrapy.org/
* https://docs.scrapy.org/en/latest/intro/overview.html
* https://docs.scrapy.org/en/2.11/topics/settings.html

How to run Scrapy:
1. Use PowerShell
2. scrapy runspider quotes_spider.py -o quotes.jsonl

Sidenotes: 
- had to pip install scrapy first
- had to do some troubleshooting that involved updating my PATH variable
