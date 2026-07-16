# Zeepkist Community Hub

Welcome to the **Zeepkist Community Hub**, an open core ecosystem powering the Zeepkist community’s online tools and services.

## Overview

The Zeepkist Community Hub consists of multiple interconnected projects working together to deliver a seamless competitive and social platform for Zeepkist players:

| Project                      | Role                                                                                                                      | Technologies                         | Link                                                              |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------- | ------------------------------------ | ----------------------------------------------------------------- |
| **ZeepCentraal**                  | Central monorepo for ZeepCentraal, managing runs, ghosts, times and leaderboards. Powers both the frontend website and the GTR mod. | Bun (TypeScript), ElysiaJS, PostgreSQL | [GitHub Monorepo](https://github.com/zeepkist/zeepcentraal)                    |
| **ZeepCentral Web**              | Community-facing website for ZeepCentraal                                    | Nuxt 4, Vue 3                        | [ZeepCentral](https://zeepki.st)               |
| **PostGraphile GraphQL API** | Public GraphQL API exposing flexible access to ZeepCentraal data.                                                          | Bun (TypeScript), PostGraphile | [GraphQL Playground](https://graphql.zeepki.st)   |
| **GTR Mod**                  | Zeepkist mod that supplies gameplay data to ZeepCentraal and enhances in-game functionality.                                    | C# (Unity mod)                       | [GTR Mod](https://zeepki.st/mod/zeepkist-gtr)     |

## Open Core Philosophy

The Zeepkist Community Hub embraces an **Open Core** model that:

* Provides fully open source core backend services, APIs, and community tools to ensure transparency and foster community contributions.
* Encourages collaboration and extensibility across the community website (ZeepCentral), backend, and API projects.
* Keeps deployment orchestration—such as the Docker Compose setup—closed source, delivering a streamlined, official managed hosting solution.
* Balances openness and developer flexibility with efficient, reliable official deployment and maintenance.

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
