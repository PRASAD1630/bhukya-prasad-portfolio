# Bhukya Prasad — Portfolio
Static portfolio built with Vite. Photo: `public/assets/prasad.jpg`. Resumes: `public/resumes/`.

## Run locally
    npm install
    npm run dev      # http://localhost:5173
    npm run build    # outputs dist/

## Deploy (GitHub + Vercel)
1. Create an empty repo `bhukya-prasad-portfolio` on GitHub, then:
       git init && git add . && git commit -m "Initial portfolio"
       git branch -M main
       git remote add origin https://github.com/PRASAD1630/bhukya-prasad-portfolio.git
       git push -u origin main
2. vercel.com → Sign up with GitHub → Add New → Project → import the repo.
3. Framework Preset: Vite. Build: `npm run build`. Output: `dist`. Project Name: `bhukya-prasad` → Deploy.
4. Your URL is https://<project-name>.vercel.app (Settings → Domains to view/change).
