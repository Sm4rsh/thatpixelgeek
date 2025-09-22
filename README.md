# That Pixel Geek

A lightweight React + Tailwind site with blog pages, pixel dog logo, newsletter signup, and AdSense placeholders.

## 🚀 Local Development

```bash
npm install
npm run dev
```

## 📦 Build for Production

```bash
npm run build
npm run preview
```

## 🌐 Deployment on Cloudflare Pages

1. Push this repo to GitHub
2. Go to [Cloudflare Pages](https://pages.cloudflare.com/)
3. Create a new project → connect your GitHub repo
4. Build command: `npm run build`
5. Output directory: `dist`

## ✍️ Editing Blog Posts

Edit `src/data/posts.js`. Each post has:
- `slug`: unique URL slug
- `title`: post title
- `date`: publish date
- `excerpt`: short preview
- `content`: HTML string for content

## 📊 Google AdSense

Ad placeholders are included. Replace them with your AdSense code when ready.
