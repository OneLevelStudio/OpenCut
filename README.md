# OpenCut

## Install npm and bun
* https://nodejs.org/en/download
* https://bun.com/docs/installation
```
npm --version
bun --version
```

## Development
```
cd apps/web
bun install
bun run dev
```

## Production
```
cd apps/web
bun install
bun run build
bun run start
```

## Cloudflare
* Production branch: `main`
* Framework preset: `None`
* Build command: `bun install && bunx next build`
* Build output directory: `.next`
* Root directory (advanced) - Path: `apps/web`
