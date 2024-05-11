# asklibrarian
apps that can act like librarian for papers edgeDB hackathon

scraping database linked to google scholar, scopus, pubmed, etc through API
using keyword as input and contextualized using LLM
input -> LLM1 -> database -> LLM2 -> output
input: text input
output: reference papers
LLM1: turning text input into contextualize keywords for scraping database
LLM2: turning scraped database into reference recommendations
