# Biome configuration

My shared Biome configurations.

## Installation

Install this package and its peer dependency with your favorite package manager:

```bash
# npm
npm i -D @stebeus/biome-config @biomejs/biome

# yarn
yarn add -D @stebeus/biome-config @biomejs/biome

# pnpm
pnpm add -D @stebeus/biome-config @biomejs/biome

# deno
deno add npm:@stebeus/biome-config npm:@biomejs/biome

# bun
bun add -D @stebeus/biome-config @biomejs/biome
```

## Usage

```jsonc
// biome.jsonc
{
  "$schema": "https://biomejs.dev/schemas/2.5.5/schema.json",
  "extends": ["@stebeus/biome-config"]
  // Your configuration...
}
```

## License

[MIT](LICENSE.txt)
