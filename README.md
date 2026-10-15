# Quiz Hub

Static site: `index.html` (home), `dbms-quiz.html`, `java-quiz.html`, `dbms-explanations.js`, `java-explanations.js`.

Hệ thống trắc nghiệm kèm giải thích chi tiết bằng tiếng Việt ngay sau khi trả lời từng câu hỏi và trong phần tổng kết xem lại các câu sai.

## Deploy GitHub Pages

```bash
git init -b main
git add .
git commit -m "Add quiz site"
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main
```

Repo Settings -> Pages -> Source: Deploy from a branch -> Branch: `main` / `/ (root)`.
URL: `https://<username>.github.io/<repo>/`
