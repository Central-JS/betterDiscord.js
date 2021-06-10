# Example usage
```javascript
// Example - 1
const betterDiscord = require("betterDiscord.js");
const Discord = betterDiscord(require("discord.js"));

Discord.userLogin(false) // default value : true
Discord.unLimit(false) // default value : true

// Example - 2
const betterDiscord = require("betterDiscord.js");
const Discord = betterDiscord(
  require("discord.js"),
  {
    "user_login": true,
    // default value : false
    "unlimit": true
    // default value : false
  }
);
```
