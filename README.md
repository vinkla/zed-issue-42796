# Zed Issue Reproduction - Prettier Blade Plugin

Reproduction case for Prettier formatting issue with `prettier-plugin-blade` in Zed.

https://github.com/zed-industries/zed/issues/42796

## Setup

1. Install dependencies:

   ```sh
   pnpm install
   ```

2. Open project in Zed:
   ```sh
   zed .
   ```

## Reproduce the Issue

1. Open `unformatted.php` in Zed
2. Format the file with `Cmd+Shift+I` (macOS) or `Ctrl+Shift+I` (Linux/Windows)
3. Observe the behavior

## Verify Prettier Works via CLI

```sh
pnpm run format
```

The CLI should format the file correctly, showing the issue is specific to Zed.
