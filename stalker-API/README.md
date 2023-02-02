# `How to use? 👇🏻`
## GitHub stalker by [zahwazein](https://github.com/zahwazein/)
```bash
\\for 𝗰𝗮𝘀𝗲 based script 

case '<command-name>':{
     if (!text) return reply("Please enter a valid username")
     let gitStalker = await fetchJson(`https://api.zahwazein.xyz/stalker/github?username=${args[0]}&apikey=𝗬𝗼𝘂𝗿𝗔𝗣𝗜𝗸𝗲𝘆`)
let gitResults = `Stalking for : Github
\nId : ${gitStalker.result.id}
Git Username : ${gitStalker.result.name}
Git Username : ${gitStalker.result.login}
Git Bio : ${gitStalker.result.bio}
Node Id : ${gitStalker.result.node_id}
Account type : ${gitStalker.result.type}
Public Repo : ${gitStalker.result.public_repos}
Public Gits : ${gitStalker.result.public_gists}
Followers : ${gitStalker.result.followers}
Following : ${gitStalker.result.following}
Account Creation : ${gitStalker.result.created_at}
Account Updated : ${gitStalker.result.updated_at}
Location : ${gitStalker.result.location}
Company : ${gitStalker.result.company}
Twitter : ${gitStalker.result.twitter_username}
Email : ${gitStalker.result.email}
Account Url : ${gitStalker.result.url}`
     await bot.sendMessage(m.chat, gitResults, m)
      }
      break
```
