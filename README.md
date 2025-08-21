# Bapecord

Bapecord is a fork of [Vencord](https://github.com/Vendicated/Vencord) — the most optimized, swaggaged Discord client.

The most optimized swagged Discord client mod

<img width="1536" height="1024" alt="bapcordbanner" src="https://github.com/user-attachments/assets/da865915-a3eb-4f24-b1ad-132e99569a2c" />


## Features

-   Easy to install
-   [100+ built in plugins](https://vencord.dev/plugins)
-   Fairly lightweight despite the many inbuilt plugins
-   Excellent Browser Support: Run Vencord in your Browser via extension or UserScript
-   Works on any Discord branch: Stable, Canary or PTB all work
-   Custom CSS and Themes: Inbuilt css editor with support to import any css files (including BetterDiscord themes)
-   Privacy friendly: blocks Discord analytics & crash reporting out of the box and has no telemetry
-   Maintained very actively, broken plugins are usually fixed within 12 hours
-   Settings sync: Keep your plugins and their settings synchronised between devices / apps (optional)
## Installing Bapecord Devbuild

### Dependencies

[Git](https://git-scm.com/download) and [Node.JS LTS](https://nodejs.dev/en/) are required.

Install `pnpm`:

> :exclamation: This next command may need to be run as admin/root depending on your system, and you may need to close and reopen your terminal for pnpm to be in your PATH.

```shell
npm i -g pnpm
```

> :exclamation: **IMPORTANT** Make sure you aren't using an admin/root terminal from here onwards. It **will** mess up your Discord/Equicord instance and you **will** most likely have to reinstall.

Clone Equicord:

```shell
git clone https://github.com/bapecord/Bapecord
cd Bapecord
```

Install dependencies:

```shell
pnpm install --frozen-lockfile
```

Build Equicord:

```shell
pnpm build
```

Inject Equicord into your client:

```shell
pnpm inject
```



## Join our Support/Community Server

https://discord.gg/S7tx5stnvk

## Disclaimer

Discord is trademark of Discord Inc. and solely mentioned for the sake of descriptivity.
Mention of it does not imply any affiliation with or endorsement by Discord Inc.

<details>
<summary>Using Vencord violates Discord's terms of service</summary>

Client modifications are against Discord’s Terms of Service.

However, Discord is pretty indifferent about them and there are no known cases of users getting banned for using client mods! So you should generally be fine as long as you don’t use any plugins that implement abusive behaviour. But no worries, all inbuilt plugins are safe to use!

Regardless, if your account is very important to you and it getting disabled would be a disaster for you, you should probably not use any client mods (not exclusive to Vencord), just to be safe

Additionally, make sure not to post screenshots with Vencord in a server where you might get banned for it

</details>
