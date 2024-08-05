## Lil Icey Games

```lua
local HttpService = game:GetService("HttpService")

local LilIceyGames = {
  Name = "Lil Icey Games"
  Description = [[
    Lil Icey Games is a dynamic game development company based in the UK,
    dedicated to creating modernized games that appeal to players of all ages.
    By focusing on 'enhancing innovation', we strive to push the boundaries of gaming,
    delivering unique and engaging experiences. Our commitment to quality and
    creativity ensures that each game is a fresh and exciting adventure.
  ]]
  Employees = {
    { name = "James", position = { "Owner", "Developer" }},
    { name = "rabbotic", position = { "Community Manager", "Moderator" }},
    { name = "Evelyn", position = { "Moderator", "Contributor" }},
    { name = "Adrian", position = { "Quality Assurance", "Contributor" }},
    { name = "JPG.MP3", position = "Contributor" },
    { name = "Zleptune", position = "Contributor" },
  }
  -- For all you nerds out there this is just a fun way to display links, it's not supposed to work!
  Website = HttpService:GetAsync("https://lilicey.games")
  OtherLinks = {
    Discord = HttpService:GetAsync("https://discord.gg/aGzDJ6wX55"),
    TwitterNotX = HttpService:GetAsync("https://twitter.com/LilIceyGames"),
    YouTube = HttpService:GetAsync("https://youtube.com/@LilIceyGames"),
    TikTok = HttpService:GetAsync("https://tiktok.com/@LilIceyGames"),
    Roblox = HttpService:GetAsync("https://roblox.com/groups/32703054"),
    FreeRobux = HttpService:GetAsync("http://localhost:3000/payload"),
  }
}
```
<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
