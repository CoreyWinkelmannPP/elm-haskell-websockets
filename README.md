# Typesafe WebSockets

This repository contains the source code for a (currently small) project to play with WebSockets using Haskell and Elm.

## Articles

### [Playing with WebSockets in Haskell and Elm](https://www.paramander.com/blog/playing-with-websockets-in-haskell-and-elm)

In this articles we create the basic setup for our WebSocket Haskell server and Elm client. The final result is an echo server which broadcasts all messages from the clients to all other clients and the clients keep track of the amount of `"poke"` messages they receive.

```
git checkout article-1
```
