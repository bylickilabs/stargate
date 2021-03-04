# Discord bot using Stargate

<table border="0">
  <tr>
    <td align="center">
      Stargate is a data gateway deployed between client applications and a database. It's built with extensibility as a first-class citizen and makes it easy to use a database for any application workload by adding plugin support for new APIs, data types, and access methods.
      For more information about how to use Stargate, visit <a href="https://stargate.io/">Stargate.io</a>
    </td>
    <td align="center">
      YouTube video of Stargate
      <a href="http://www.youtube.com/watch?v=2ltVf2EscmM">
        <img src="http://img.youtube.com/vi/2ltVf2EscmM/0.jpg" alt="YouTube thumbmnail for Stargate" />
      </a>
    </td>
  </tr>
</table>

## Phase 1 Goals

- A video tutorial (ideally, 5-10 min) on how to use Stargate (serverless)
- CRUD usage of Stargate
- Discord Bot (bio, social links, timezone)

## Technologies Used 

- [DiscordJS](https://discordjs.guide) with Typescript
- [Stargate](http://stargate.io)

## Quickstart

1. fork the project
1. clone project `git clone https://github.com/<YOUR-USERNAME>/stargate`
1. navigate into the project `cd stargate`
1. `cp .env.example .env`
1. add the respective env-vars to the .env file
  - [generating Discord bot token](https://discordjs.guide/preparations/setting-up-a-bot-application.html#keeping-your-token-safe)
  - [making AUTH token for Stargate](https://stargate.io/docs/stargate/1.0/developers-guide/authnz.html#_generate_an_auth_token)
1. install dependencies `npm install`
1. install husky helpers `npm run prepare`

## Docs

- [Project board v0.1](https://github.com/eddiejaoude/stargate/projects/1) of `to do`, `in progress`, `done`
- How to edit project [Labels](docs/labels.md)
