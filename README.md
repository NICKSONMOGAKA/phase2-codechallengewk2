# Phase 2 Code Challenge: Bot Battlr

## Instructions

For this project, you’ll be building out a React application that displays a
list of available bots, among other features.

## Setup

After cloning the project:

1. Run `npm install` in your terminal.
2. Run `npm run dev`. 

The base URL for your backend is in vercel look in my github repos you will find it.

## What You Already Have

`BotPage` is the highest component below App, and serves as the main container
for all of the pieces of the page.


## Core Deliverables

As a user, I should be able to:

- See profiles of all bots rendered in `BotCollection`.
- Add an individual bot to my army by clicking on it. The selected bot should
  render in the `YourBotArmy` component. The bot can be enlisted only **once**.
  The bot **does not** disappear from the `BotCollection`.
- Release a bot from my army by clicking on it. The bot disappears from the
  `YourBotArmy` component.
- Discharge a bot from their service forever, by clicking the red button marked
  "x", which would delete the bot both from the backend and from the
  `YourBotArmy` on the frontend.

Author
Nickson Mogaka