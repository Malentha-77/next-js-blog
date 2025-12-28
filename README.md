# next-js-blog
A modern, fast blog built with Next.js featuring static site generation and markdown support.

## ✨ Features

- 📝 **Markdown Blog Posts** - Write your posts in simple markdown files
- ⚡ **Static Site Generation** - Lightning-fast pages pre-rendered at build time
- 🎨 **Clean & Minimal Design** - Beautiful, responsive layout
- 🔗 **Dynamic Routing** - Automatic page generation for each blog post
- 📅 **Date Formatting** - Elegant date display using date-fns
- 🚀 **API Routes** - Serverless functions support

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/username/nextjs-blog.git
cd nextjs-blog
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 📝 Adding Blog Posts

1. Create a new `.md` file in the `posts/` directory
2. Add frontmatter at the top:
```markdown
---
title: 'Your Post Title'
date: '2024-01-01'
---

Your post content here...
```

3. The post will automatically appear on your blog!

## 🛠️ Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm start` - Start production server

## 📁 Project Structure

```
nextjs-blog/
├── components/     # React components
├── lib/           # Utility functions
├── pages/         # Next.js pages & API routes
├── posts/         # Markdown blog posts
├── public/        # Static assets
└── styles/        # CSS modules
```

## 🎯 Learn More

This project is based on the [Next.js tutorial](https://nextjs.org/learn). It demonstrates:

- Static Site Generation (SSG) with `getStaticProps`
- Dynamic routes with `getStaticPaths`
- Markdown processing with `remark`
- CSS Modules for styling

## 📄 License

MIT

---

Built with ❤️ using Next.js


