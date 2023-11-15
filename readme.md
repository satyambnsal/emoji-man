## Emoji Man

Eat to survive workshop.

### Resources:

- [dojobook](https://book.dojoengine.org/)
- [Cairo book](https://github.com/cairo-book/cairo-book.github.io/)
- [discord](https://discord.gg/dojoengine)
- [awesome dojo](https://github.com/dojoengine/awesome-dojo)

## Getting started in the Demo

### Prerequisites

Install dojo:

```
curl -L https://install.dojoengine.org | bash
```

Then install dojoup:

```
dojoup
```

### (Optional) Try out the starter first

`git clone https://github.com/dojoengine/dojo-starter`

### Step 1: Init main project

`git clone https://github.com/dojoengine/emoji-man`

a. Initialising the project
b. Looking at the project structure
c. Looking at the Scarb
d. Cairo explanation

### Step 2: Your first model

a. Thinking about model structure
b. Creating a model and their state structure. 101 on [ECS](https://github.com/SanderMertens/ecs-faq)
c. Dojo is not purely ECS

### Step 3: Your first system

a. Creating a system - it's just a contract
b. Adding a new system
c. Run building via sozo to test

### Step 4: Adding a new model to a system

a. Adding a new model
b. Adding a trait!!
c. Using the trait in a system
d. Running build to check

### Step 5: Sozo and the cli

a. Deeper into sozo
b. Spinning Katana up
c. Spinning up torii and pointing to world

### Step 6: Clean up

a. clean up of code

### Step 7: Testing

a. Testing structure
b. Writing a world deploy test
c. Running the test

### Step 8: Deploying to Katana

a. Deploying and debugging

### Step 8: Client running

a. Running the client
b. Generating models via npm
c. Explaining the client structure - this is just one client, you can have many
d. Explaining torii wasm

### Step 9: New model and syncing

a. Adding new model to contracts
b. resyncing the client

### Step 10: Spinning up slot and deploying remotely

a. What is [slot](https://github.com/cartridge-gg/slot)?
`slot auth login`
b. Deploying to Katana
`slot deployments create <Project Name> katana`
c. Deploying a client to vercel - `use your own vercel account`
d. Multiplayer - share live link

## Next Steps

### Bonus 1: Optimistc Rendering

- Use RECS optimisc rendering to render the player in the client before the tx is confirmed

### Bonus 2: Show energy levels in the client

- Use RECS to show the energy levels in the client

### Bonus 3: Noise in map in Cairo and in Client

- Use [cubit](https://github.com/influenceth/cubit) simplex noise to restrict movement over mountains
- [noise](https://github.com/influenceth/sdk/blob/master/src/utils/simplex.js)

### Bonus 4: Add a collectables

- Add a way to spawn collectables on the map and allow players to collect them
