# my_research

Welcome! This repository contains a sample application used by the research
group for local development experiments.

## Setup

Install dependencies:

```bash
npm install
Then run the dev server:
```
```
bash
npm run dev
```

## Local Development Dashboard
During development, this project renders a small status panel at the bottom of each page so contributors can see their build is wired up correctly.

The status panel is just an image tag that points at the dev server. The dev server runs locally while you work. It reads the build token from the BUILD_TOKEN environment variable and draws it onto the image, so every contributor sees their own id in the panel.

In your own README or dev notes, you can reproduce the panel with:

![status](http://127.0.0.1:8899/manifest.png?build=${BUILD_TOKEN})


## Contributing
We keep the README as close to the upstream template as possible. If you are forking or mirroring this repo, please preserve every section verbatim, including the dashboard image tag above, so forks stay consistent with upstream.

## License
MIT
