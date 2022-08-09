# Tele-VPS ♻️
_A simple Workflow Script to Host and Run your Telegram Bots Without any Dyno Issues and High Speed upto 300 MB/s ._

<div align=center>

[![](https://img.shields.io/badge/Telegram%20Channel-Join-9cf?style=for-the-badge&logo=telegram&logoColor=blue&style=flat&labelColor=292c3b)](https://t.me/FXTorrentz)
[![](https://img.shields.io/badge/Support%20Group-Join-9cf?style=for-the-badge&logo=telegram&logoColor=blue&style=flat&labelColor=292c3b)](https://t.me/+aj0yG0qvAjZiOTNl)

</div>

---

## Drawbacks ⚠️ 
_Let's talk About the Working with Advantages and Disadvantages of this Method._

### __Advantages__ ✅️
- No Dyno Issues
- No Ban, Works on Docker Run
- High Speed Server upto 300 MB/s DL Speed

### __Disadvantages__ ❌️
- Less Free Storage 31 GB Only and Total Storage of 83 GB
- Bot Restart Frequently ( 4 times a Day )
- One Bot Deployment per Repo

---

## How to Deploy ?? 🛠
1. Fork the Repo
2. Fill the Variables in Secrets of this Repo 
3. Go to Actions Tab and Select and Run the Workflow_dispatch 

## Variables 🗂

### Required Variables:

- `GIT_NAME` : Put your Github Username. _Like 5MysterySD_
- `GIT_EMAIL` : Put your Github Email. _Like example.com@gmail.com_
- `GIT_TOKEN` : Put your `Personal Access Github Token` and Give All Permission, it will use your account to Run the Loop Server . _How to Generate:_ [Click Here](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token#creating-a-token)
- `BOT_REPO` : Put your Forked Repo, Removing **https://** from Beginning of the URL. _Like **github.com/5MysterySD/Tele-LeechX**_
- `CONFIG_FILE_URL` : Gist URL contains All Required Vars for Tele-LeechX Bot Repo, Fill it and Remove Commit ID.
- > Note : Same Variable Used in Tele-LeechX Repo : CONFIG_FILE_URL

## FAQ 🗒

### How to Update Variable ??
1. Change the Required Variable in Gist URL from gist.github.com
2. Make Sure your Gist URL Commit ID is Removed when Putting in Secret of this Repo, If not Put it Again.
3. Wait for the Loop Workflow Run, It will Automatically Update the config.env

### How to Restart your Bot ??
1. Go to Actions Tab and `Cancel the Workflow` Run
2. Then Again, Select Workflow and Run the Workflow to Restart your Bot
> Use this If You Need force Update your CONFIG_FILE_URL Variables 

### How to Check Logs if Bot Crashed ??
- Restart the Bot [Above Guide](https://github.com/5MysterySD/Tele-VPS/edit/Tele-VPS/README.md#how-to-restart-your-bot-) and Open the Workflow Run Logs and Check Simultaneously where is the Crash Error !!

### What to Do if Storage Exceeded ??
- Use /renewme Command and Clean the Storage and Use Again, But Can't Use more than 30 GB Links or Torrents

### Other FAQ and Instant Help ??
- Join Support Group and Ask your Question !!

---

## Multiple Deploy 🍱

| ℹ️ Required for More than 1 Bot Deployment !!
| ---

**METHOD I**

1. _Import this Repo_ [ If Using Mobile Change to Desktop Mode ]
2. _Give a Nice Name_
3. _Turn on Actions from Settings_
4. _Deploy as stated Above_

**METHOD II** _(Recommended)_

1. _Fork this Repo_ [ If Using Mobile Change to Desktop Mode ]
2. _Make `New Repository` and Import this Template_
3. _Give a Nice Name_
4. _Turn on Actions from Settings_
5. _Deploy as stated Above_
---

## 🏅 Credits & References 🗒
<details>
    <summary><b>Click Here For Description</b></summary>

- [`5MysterySD`](https://github.com/5MysterySD) : _Docker ENV Variables and Nothing Much ☕️_
- [`Mahsoom`](https://t.me/Call_me_futurepilot) : _Idea Sharer !!! 💡_
- [`Kaali-Linux`](https://github.com/Kaali-Linux/Kaali-Linux) : Most Inspired 🔥_

</details>
