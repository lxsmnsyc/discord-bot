# discord-bot

## Development

### Requirements

- Node
- Yarn (optional)

### Setup

Fork the project first, clone the repo locally then run:

```bash
yarn install
```

or

```bash
npm install
```

You must also create a `.env` in the root directory with the following values:

```env
DISCORD_BOT_PREFIX=!
DISCORD_BOT_TOKEN=my_token
```

### Running

Run the build command first:
```bash
yarn build
```
or
```bash
npm run build
```

then to run the project:
```bash
node dist
```