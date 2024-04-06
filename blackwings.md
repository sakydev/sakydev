# Project: BlackWings
![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white) ![Chi](https://img.shields.io/badge/Chi-02A9E0?logo=go&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white) ![Cobra](https://img.shields.io/badge/Cobra-02A9E0?logo=go&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)


### What
A command line tool to search across your entire digital footprint. This will include essential apps like Gmail, Drive, Dropbox, Jira, Slack, Confluence and more.

### Why
I often encounter situations where I remember something but remember where it exists. This can include documentation, technical discussions, and more. I felt the need for a uniform tool that has wings into my essential apps and can retrieve what I'm looking for. 

### How
A Go-powered CLI built with Cobra and integrates with popular APIs. It authenticates once and uses tokens for further refreshses. You can add an unlimited number of accounts. Go is excellent choice because app requires calls to several external APIs. Go comes with powerful concurrency and Goroutines can process tasks in parallel. 
