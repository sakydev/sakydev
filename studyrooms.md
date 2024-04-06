# Project [StudyRooms](https://knowunity.com/about/download)
![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white) ![Chi](https://img.shields.io/badge/Chi-02A9E0?logo=go&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white) ![AWS SQS](https://img.shields.io/badge/AWS%20SQS-569A31?logo=amazon-aws&logoColor=white) ![Websockets](https://img.shields.io/badge/Websockets-4A154B?logo=websocket&logoColor=white) ![Goroutines](https://img.shields.io/badge/Goroutines-00ADD8?logo=go&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-FF6C2C?logo=grafana&logoColor=white) ![Sentry](https://img.shields.io/badge/Sentry-362D59?logo=sentry&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

### What
Live subject concentrated chat rooms where users can study together in Pomodoro focus/break style

### Why
The company had 10M+ app users for an education-centric product. The students wanted to study together with others without having to leave their homes. They also wanted the possibility to ask for help when stuck on certain problems. Features included:

- Group chats with collaboration
- Media and homework scan sharing
- Focus/pause timers
- Warn users if inactive for 15 minutes
- Kickout users if inactive for 20 minutes
- Notify user followers about study rooms

### How
I was responsible for entire backend implementation. Go, Chi, Docker, and Postgres were primary tools for API and documented with Swagger. Websocket and SQS were used to communicating between different microservices and send notifications to users. Goroutines were included to help tackle intensive tasks like sending notifications to thousands of users.
