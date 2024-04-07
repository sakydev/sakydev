# Project HoneyResume
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white) ![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white) ![Blade](https://img.shields.io/badge/Blade-FF2D20?logo=laravel&logoColor=white) ![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?logo=bootstrap&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![Selenium](https://img.shields.io/badge/Selenium-43B02A?logo=selenium&logoColor=white) ![Scrapy](https://img.shields.io/badge/Scrapy-2C2D72?logo=scrapy&logoColor=white)

### Why
My sister-in-law was working manually combing through tons of emails and processing them individually. She worked for a company that offered services to clients for promoting their resumes. The process was dead-slow and she could only send a few dozen emails per day. 

Initially, I built a command line tool for automating her process. This later spawned into full full-fledged project with dashboards, crawlers, and more. We eventually closed the business but had a fun run.

### What
A system for automating crawling and distribution of resumes based on client specifications

### How
I split the system into three parts

**Dashboard**  
This enabled creation of new clients, the monitoring of running processes, payments and notifications. A non-technical person could run the whole thing without looking underneath hood. 

**Crawler**  
A Scrapy powered crawling service. This ran several times per day. The goal was to scrap dozens of job listing websites and extract company emails, industry details and job specifications.

**Distributor**  
This background service relied on client configurations and iteratively distributed resumes to wide array of companies crawled by Scrapy service

