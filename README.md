<div align="center">
  <br />
  <br />
  <img src="https://user-images.githubusercontent.com/99760654/185508014-af2ed79c-daba-417d-be7e-9103eab67180.png" width="600" />
  <br />
  <br />
  <a href="//github.com/atomdevelops/minecraftjs/issues">Issues </a> • <a href="//github.com/atomdevelops/minecraftjs/releases"> Releases </a> • <a href="//minecraft.atomdev.cf"> Homepage </a>
  <br />
  <br />
  <img src="https://img.shields.io/npm/dm/@atomdevelops/minecraftjs" />
  <img src="https://img.shields.io/npm/v/@atomdevelops/minecraftjs?label=version" />
  <p>A library to view statistics for Minecraft servers and players.</p>
</div>

# 🚀 Install

You have to install the library from the `npm` registry. You can do so by executing the following command:

For `npm`:
```
npm i @atomdevelops/minecraftjs
```

For `yarn`:
```
yarn add @atomdevelops/minecraftjs
```

For `pnpm`:
```
pnpm add @atomdevelops/minecraftjs
```

# 🦄 Usage
MinecraftJS is pretty simple to get started with. All you need to do is initialize the `MinecraftClient` and you're all set!

> **Note**: This library does require you to have an API key. You can find information on how to do so in our [documentation](//mc.atomdev.cf).

```js
import { MinecraftClient, Server } from "@atomdevelops/minecraftjs";
const client = new MinecraftClient("API 1", "API 2");
// Replace "API 1" and "API 2" to the different API keys mentioned in the documentation.

const res = new Server("hypixel.net")

console.log(`${res.ip}\n${res.playerCount);
```

You can find the documentation on everything the library is capable of [here](//mc.atomdev.cf).

# 📘 Documentation

Our [API Documentation](//mc.atomdev.cf) is **currently unavailable**. But, this is subject to change very soon. For now, this library is highly experimental and it is not recommended to use it for production.

