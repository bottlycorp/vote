# Vote for Bottly

An express application so that when a vote has arrived, it is given advantages on the bot

### Installation:

Use PNPM or PNPM and install the pacakges `pnpm install` or `npm install`.

Set the required environment variables 
```env
DATABASE_URL="Your database URL if you want edit data when a user vote"
// If you use Railway, define this environment variable for set Node.JS 18
// NIXPACKS_NODE_VERSION=18
PORT=3000
TOPGG_TOKEN="https://top.gg/bot/:yourAppID/webhooks"
```

### Initialize your prisma

Use the command `npx prisma db pull` to retrieve your database if you have already created tables

Or create your models and then do `npx prisma db push` to send your changes to the database

Then do `npx prisma generate` to generate your types. 

### Lauch the app

Use `pnpm` or `npm`, `run dev` or `run start`

# Usage:
![Logger](https://media.discordapp.net/attachments/739077279551848460/1097975344931283064/image.png)
