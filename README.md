# francisyhou.github.io

Plain static site. No build step. Edit the .html files directly; style.css is the only stylesheet.

Deploy (first time):
1. On GitHub, create a new public repository named exactly `francisyhou.github.io`.
2. In this folder:
   git init && git add . && git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/francisyhou/francisyhou.github.io.git
   git push -u origin main
3. Wait a minute, then open https://francisyhou.github.io

Update later: edit files, then `git add . && git commit -m "..." && git push`.
