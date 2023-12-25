# LinkHub

LinkHub is an experimental link-in-bio tool, where the data lives in the URL. 

![link-hub-links-vercel-app](https://github.com/Ashutosh102/linkhub/assets/75971776/b8b6d957-2a93-4511-afdb-c153e66f851f)


> **Note**
> Since the URL can become very long, it's better to use a link shortener like https://dub.co

Here's a demo page
https://link-hub-links.vercel.app/1?data=eyJuIjoiRGV2IEFzaHUiLCJkIjoiV0VCIERFVkVMT1BFUiBBTkQgRlJFRUxBTkNFUiIsImkiOiJodHRwczovL2RldmZvbGlvLWRldmFzaHUubmV0bGlmeS5hcHAvc3RhdGljL21lZGlhL3Byb2ZpbGUuNmZjNmZjMWFkMTBjMzhhY2FkYjEucG5nIiwiZiI6Imh0dHBzOi8vd3d3LmZhY2Vib29rLmNvbS9hc2h1dG9zaC5tb2hhbnR5LjU4OTU4IiwidCI6Imh0dHBzOi8vdHdpdHRlci5jb20vQXNodXRvczU2Njk1Nzc0P3M9MDkiLCJpZyI6Imh0dHBzOi8vd3d3Lmluc3RhZ3JhbS5jb20vZGV2X2FzaHVfMTAyLyIsImUiOiJhc2h1dG9zaG1vaGFudHkzODE1QGdtYWlsLmNvbSIsImdoIjoiaHR0cHM6Ly9naXRodWIuY29tL0FzaHV0b3NoMTAyIiwidGciOiJodHRwczovL3QubWUvQXNodXRvc2gzODE1IiwidyI6Iis5MTc3NDkwNjc4MjAiLCJ5IjoiaHR0cHM6Ly95b3V0dWJlLmNvbS9AYXNodXRvc2htb2hhbnR5NzU3MyIsImwiOiJodHRwczovL3d3dy5saW5rZWRpbi5jb20vaW4vZGV2YXNodSIsImxzIjpbeyJsIjoiTXkgV2Vic2l0ZSIsImkiOiJwaDpnbG9iZS1kdW90b25lIiwidSI6Imh0dHBzOi8vZGV2Zm9saW8tZGV2YXNodS5uZXRsaWZ5LmFwcC8ifSx7ImwiOiJBbWF6b24gd2lzaGxpc3QiLCJpIjoiYW50LWRlc2lnbjphbWF6b24tb3V0bGluZWQiLCJ1IjoiaHR0cHM6Ly9hbWF6b24uaW4ifSx7ImwiOiJSZWFjdCBKUyBjb3Vyc2UiLCJpIjoiZ3JvbW1ldC1pY29uczpyZWFjdGpzIiwidSI6Imh0dHBzOi8vcmVhY3Rqcy5vcmcvIn0seyJsIjoiRG9uYXRlIGZvciBvdXIgY2F1c2UiLCJpIjoiaWNvbm9pcjpkb25hdGUiLCJ1IjoiaHR0cHM6Ly93aG8uaW50In0seyJsIjoiRG93bmxvYWQgbXkgcmVzdW1lIiwiaSI6InBoOmZpbGUtcGRmIiwidSI6Imh0dHBzOi8vZHJpdmUuZ29vZ2xlLmNvbS9maWxlL2QvMWpzYXY5cEp4UzhnQmhZbUpRbkkxdmlraTF3Y1dIbUhFL3ZpZXc/dXNwPXNoYXJpbmcifV19

The data is converted to a base 64 string which we onelink uses as a query parameter. I have tried to reduce the json keys to be as small as possible

Roadmap.
1. Templates - make different templates, the `/1` after the host is basically a template here.
2. Refactor code - a lot of repeated boilerplate code is added here - refactor it properly.

## Setup locally

Make sure to install the dependencies:

```bash
# yarn
yarn install

# npm
npm install

# pnpm
pnpm install --shamefully-hoist
```

## Development Server

Start the development server on http://localhost:3000

```bash
npm run dev
```

## Production

Build the application for production:

```bash
npm run build
```

Locally preview production build:

```bash
npm run preview
```

Checkout the [deployment documentation](https://v3.nuxtjs.org/guide/deploy/presets) for more information.
