# Project VirailSearch
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white) ![Phalcon](https://img.shields.io/badge/Phalcon-4F5B93?logo=phalcon&logoColor=white) ![Elastic Search](https://img.shields.io/badge/Elastic_Search-005571?logo=elasticsearch&logoColor=white) ![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?logo=vue.js&logoColor=white) ![Cypress](https://img.shields.io/badge/Cypress-17202C?logo=cypress&logoColor=white) ![Scrapy](https://img.shields.io/badge/Scrapy-2C2D72?logo=scrapy&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)


### What
A travel route planning service, spanning across regions including Europe, UK, US, Russia, India, and more. The app integrates with dozens of partner APIs to recommend the fastest routes and affordable accommodations.	I helped extract monolithic app into multiple microservices for easier development and onboarding. 

### How
The original app was built in Phalcon framework. There had been layers and layers of legacy code. API versions one after another and classes jumbled together with weird combinations. Even though it worked, codebase had become unmaintainable and hard to debug. 

I devised a microservice architecture. The monolith was divided into three separate layers. These were built on Laravel and Scrapy with RabbitMQ as a communication bridge. 

**Search**  
I implemented Laravel for core search API which was responsible for answering to millions of user calls. The search service relied on data and crawling services. 

**Data**  
It took a search query (from and to) and split it into all different possible combinations. Then devised what resources should be crawled based on internal formulas. 

**Crawl**  
Scrapy-powered service responsible for pulling data from 50+ sources including API partners and web scrapping. 
