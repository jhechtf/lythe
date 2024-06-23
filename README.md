# Lythe

Lythe (/laɪð/, sounds like "five" with an "L" instead of an "f") will (hopefully) be an alternative full-stack Svelte framework, similar to SvelteKit.

## Why?

I use Svelte and SvelteKit a lot; my current day job uses SvelteKit for our main product,
and almost all of my side projects are written with SvelteKit.

However, I've worked with Next.js projects and I really like the idea of being able to 
create RPC calls on-the-fly to be able to utilize the "same" function calls in the back-end and the front-end. 

In looking this up, I've also noticed that there's a severe lack of WebSocket support officially from the SvelteKit team. I want Lythe to be that inspiration that the SvelteKit team will ~~shamelessly steal~~ use as inspiration, assuming Lythe gains any amount of notoriety.

## Goals

So what _exactly_ am I aiming for?

### Things I think SvelteKit does right

1. File system based routing
2. Overall data loading pattern

### Things I wish SvelteKit did (or did better)

1. I wish there was a way to request additional sets of information after the initial load
without needing to jerry-rig something like [tRPC](https://github.com/trpc/trpc) or GraphQL into SvelteKit.
2. WebSocket communication built into the framework

