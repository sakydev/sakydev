# Project: [Fluxton](https://github.com/fluxton-io/fluxton)
![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white)
![Echo](https://img.shields.io/badge/Echo-132023?logo=go&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white)
![PostgREST](https://img.shields.io/badge/PostgREST-0093B5?logo=postgresql&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?logo=traefikproxy&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)


### What
The Fluxton [repo](https://github.com/fluxton-io/fluxton) will do a much better job of explaining

### Why
I built lots of things to tinker with. And I have friends who love doing the same. We often find ourselves excited about an idea. But it either requires using existing services that you don't have much control over. Or building your own infrastructure from scratch. Both options are not optimal.
Fluxton comes a solution. It's blazing fast due to Go's performance, runs anywhere with Docker containers and gives tools out of box to bring ideas to reality. 

### How
```mermaid
graph TD
    A[User Visits Platform] --> B[Creates New Project]
    B --> C[Provision Dedicated PostgreSQL Database]
    C --> D[Initialize Core Tables]

    D --> E[Launch New PostgREST Instance]
    E --> F[Assign Dynamic Labels for Traefik Routing]

    F --> G[Traefik Reverse Proxies Requests]
    G --> H[Expose Dynamic REST Endpoints via PostgREST]

    H --> I[Row Level Security Policies Enforced]
    H --> J[Support Full CRUD Based on Auth Context]

    B --> K[Auto-Generate Dynamic Forms & Fields]
    K --> L[Apply Field Validations & Trigger Rules]

    B --> M[Optional: Connect Storage Driver]
    M --> N[Choose: S3, Backblaze, Dropbox, etc.]
    N --> O[Store/Serve Files with Metadata]

    style A fill:#e6f7ff,stroke:#333,stroke-width:2px
    style B fill:#ccf2ff,stroke:#333,stroke-width:2px
    style C fill:#b3ecff,stroke:#333,stroke-width:2px
    style D fill:#99e6ff,stroke:#333,stroke-width:2px
    style E fill:#80dfff,stroke:#333,stroke-width:2px
    style F fill:#66d9ff,stroke:#333,stroke-width:2px
    style G fill:#4dd2ff,stroke:#333,stroke-width:2px
    style H fill:#33ccff,stroke:#333,stroke-width:2px
    style I fill:#1ac6ff,stroke:#333,stroke-width:2px
    style J fill:#00bfff,stroke:#333,stroke-width:2px
    style K fill:#e6ffe6,stroke:#333,stroke-width:2px
    style L fill:#ccffcc,stroke:#333,stroke-width:2px
    style M fill:#ffffcc,stroke:#333,stroke-width:2px
    style N fill:#ffff99,stroke:#333,stroke-width:2px
    style O fill:#ffff66,stroke:#333,stroke-width:2px
```
