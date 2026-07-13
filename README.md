# roblox-game

A Roblox game project managed with [Rojo](https://rojo.space/).

## Structure

- `default.project.json` — Rojo project file that maps folders on disk to
  Roblox instances.
- `src/ServerScriptService/` — server-side scripts. Files here are synced into
  the game's `ServerScriptService` container.

## Scripts

- `src/ServerScriptService/HelloFromAI.server.luau` — prints `Hello from AI`
  to the output console when the server starts.

## Running it

1. Install [Rojo](https://rojo.space/docs/) and its Roblox Studio plugin.
2. From the project root, start the sync server:

   ```sh
   rojo serve
   ```

3. In Roblox Studio, connect to the Rojo server and press **Play**. You should
   see `Hello from AI` in the Output window.
