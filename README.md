# JioSaavn API

![GitHub License](https://img.shields.io/github/license/EchoMusicApp/jiosaavn-api)
![GitHub Release](https://img.shields.io/github/v/release/EchoMusicApp/jiosaavn-api)

An unofficial API for downloading high-quality songs, albums, playlists, and more from [JioSaavn](https://jiosaavn.com).

## Quick Links
- **Base URL:** `https://saavn.echomusic.fun/api`
- **Documentation:** [saavn.echomusic.fun/docs](https://saavn.echomusic.fun/docs)
- **Changelog:** [CHANGELOG.md](CHANGELOG.md)

## Running Locally

1. Clone the repository:
   ```sh
   git clone https://github.com/EchoMusicApp/jiosaavn-api
   cd jiosaavn-api
   ```

### Using Docker
```sh
docker-compose up
```

### Manually

> [!NOTE]
> You need `Bun(1.0.29+)` or `Node.js(v20+)`

2. Install the dependencies and start the server:
   ```sh
   bun install
   bun run dev
   ```

## Deployment

You can deploy your own instance of the JioSaavn API to Cloudflare Workers or Vercel.

<a href="https://deploy.workers.cloudflare.com/?url=https://github.com/EchoMusicApp/jiosaavn-api">
  <img src="https://deploy.workers.cloudflare.com/button" alt="Deploy with Cloudflare Workers" height="32" />
</a>
<a href="https://vercel.com/new/clone?repository-url=https://github.com/EchoMusicApp/jiosaavn-api">
  <img src="https://vercel.com/button" alt="Deploy with Vercel" height="32" />
</a>

## License
Distributed under the [MIT License](LICENSE).
