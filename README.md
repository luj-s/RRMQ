# Roblox MessagingService matchmaking queues
Simple global MessagingService matchmaking system with queues.

# Installation
To use RMMQ, you can install the [Wally package](https://wally.run/package/luj-s/rmmq), use [the Toolbox model](https://create.roblox.com/marketplace/asset/15528670427) or get [the Roblox package](https://create.roblox.com/marketplace/asset/15528694525).

# API

## Functions

### Ready
Tells the server to look for an available queue and join it, or make a new one.

### Unready
Tells the server to make the client leave the queue it is in.

## Events

### ClientJoinedQueue -> QueueAccessCode: string
Fires when the client joined a queue, returning its access code.

### PlayerJoinedQueue -> PlayerUserId: number
Fires when a player joins the client's queue, returning his UserId.

### PlayerLeftQueue -> PlayerUserId: number
Fires when a players leaves the client's queue, returning his UserId.

### GameStarting -> void
Fires when the client's queue starts teleporting players to the game place.
