# Zeepkist Community Hub

Welcome to the **Zeepkist Community Hub**, an open core ecosystem powering the Zeepkist community’s online tools and services.

## Overview

The Zeepkist Community Hub consists of multiple interconnected projects working together to deliver a seamless competitive and social platform for Zeepkist players:

| Project                      | Role                                                                                                                      | Technologies                         | Link                                                              |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------- | ------------------------------------ | ----------------------------------------------------------------- |
| **Backend**                  | Central backend service managing runs, ghosts, times, and leaderboards. Powers both the frontend website and the GTR mod. | Bun (TypeScript), PostgreSQL, Docker | [Backend](https://github.com/zeepkist/backend)                    |
| **PostGraphile GraphQL API** | Public GraphQL API exposing flexible access to the backend data.                                                          | Node.js, PostGraphile, OpenTelemetry | [PostGraphile GitHub](https://github.com/zeepkist/postgraphile)   |
| **ZeepCentral**              | Community-facing website showcasing leaderboards, records, tournaments, and user data.                                    | Nuxt 4, Vue 3                        | [ZeepCentral](https://github.com/zeepkist/zeepkist)               |
| **GTR Mod**                  | Game mod that supplies gameplay data to the backend and enhances in-game functionality.                                    | C# (Unity mod)                       | [GTR Mod on mod.io](https://mod.io/g/zeepkist/m/zeepkist-gtr)     |

## Open Core Philosophy

The Zeepkist Community Hub embraces an **Open Core** model that:

* Provides fully open source core backend services, APIs, and community tools to ensure transparency and foster community contributions.
* Encourages collaboration and extensibility across the community website (ZeepCentral), backend, and API projects.
* Keeps deployment orchestration—such as the Docker Compose setup—closed source, delivering a streamlined, official managed hosting solution.
* Balances openness and developer flexibility with efficient, reliable official deployment and maintenance.

## Project Details

### Backend

The Backend is the heart of the Hub, providing:

* Secure REST APIs for mod and frontend communication.
* Persistent storage and fast retrieval of runs, ghosts, and records.
* Database migrations and schema management via Drizzle ORM.
* Scheduled jobs for leaderboards, history, and data upkeep.
* Integration with external services like Steam, Discord and Wasabi S3.

*Requires Bun runtime and PostgreSQL.*

### PostGraphile GraphQL API

* Exposes a powerful and customizable GraphQL endpoint backed by PostgreSQL.
* Supports complex queries and subscriptions with OpenTelemetry tracing.
  
*Requires PostgreSQL.*

### ZeepCentral Frontend

* User-friendly website displaying world records, personal bests, tournament results and community data.
* Built with modern web technologies (Nuxt 4, Vue 3) for performance and scalability.
* Integrates seamlessly with the backend APIs.
  
*Requires Bun runtime.*

### GTR Mod

* Enhances the Zeepkist gameplay experience.
* Collects and submits gameplay data (times, ghosts) directly to the backend.
* Enables advanced in-game overlays and functionality tied to community data.
  
*Requires .Net runtime.*

## Contributing

Community contributions are warmly welcomed! Please see individual project repositories for contribution guidelines.

* Report bugs or request features via issues.
* Submit pull requests with improvements or fixes.

## License

All open core projects are licensed under the [MIT License](LICENSE).

## Links

* [Zeepkist Community Hub on GitHub](https://github.com/ZeepkistCommunityHub)
* [ZeepCentral website](https://zeepki.st)
* [GTR Mod on mod.io](https://mod.io/g/zeepkist/m/zeepkist-gtr)
* [Official Zeepkist Game](https://store.steampowered.com/app/1440670/Zeepkist/)
