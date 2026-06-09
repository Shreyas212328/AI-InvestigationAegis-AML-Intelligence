# Deployment Guide

1. npm install
2. npm run build
3. Push to GitHub
4. Import repository into Vercel
5. Framework: Vite
6. Build Command: npm run build
7. Output Directory: dist

Create vercel.json:

{
  "rewrites": [
    {
      "source": "/(.*)",
      "destination": "/"
    }
  ]
}
