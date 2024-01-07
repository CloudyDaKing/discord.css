# discord.css
### A simple python package to use css for discord api

## Installation
 run ``pip install discordcss```
 run discordcss <file path> to run bot


## Documentation

no docs, view example below:

```css

.client {
    token: "";
    prefix: "!"
}

.command{
    command: "ping";
    description: "get bot latency";
    response: "Pong!";
}

.command{
    command: "bugsy";
    description: "get bot commands";
    response: "Hi bugsy!";
}

.onjoin{
    channel_id: "general";
    response: "Hello World!";
}

.onleave{
    channel_id: "general";
    response: "Hello World!";
}
```
