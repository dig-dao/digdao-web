# Dig DAO website

This project is for content management for the [Dig DAO website](https://digdao.jp/).

This code base is based on [Astro](https://astro.build/), which is a web framework for content-driven websites using Reactjs.

We use [Astroplate](https://github.com/zeon-studio/astroplate), developed by [Zeon Studio](https://zeon.studio/), as our base theme.

## 🚀 Getting Started

### 📦 Dependencies

- astro 2.3+
- node v18+
- npm v9.5+
- tailwind v3.3+

### 👉 Install Dependencies

```bash
npm install
```

### 👉 Development Command

```bash
npm run dev
```

### 👉 Build Command

```bash
npm run build
```

### 👉 Build and Run With Docker

```bash
docker build -t astroplate .
# or
# docker --build-arg INSTALLER=npm build -t astroplate .
# or
# docker --build-arg INSTALLER=pnpm build -t astroplate .

docker run -p 3000:80 astroplate
# or
# docker run --rm -p 3000:80 astroplate
```

To access the shell within the container:

```bash
docker run -it --rm astroplate ash
```

<!-- reporting issue -->
## 🐞 Reporting Issues

We use GitHub Issues as the official bug tracker for this Website. Please Search [existing issues](https://github.com/dig-dao/digdao-web/issues). It’s possible someone has already reported the same problem.
If your problem or idea has not been addressed yet, feel free to [open a new issue](https://github.com/dig-dao/digdao-web/issues).

<!-- licence -->
## 📝 License

Copyright (c) 2023 - Dig DAO contributors

**Code License:** Released under the [MIT](https://github.com/dig-dao/digdao-web/blob/main/LICENSE) license.
