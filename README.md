![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=vytorsouzadev&show_icons=true&theme=radical)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=vytorsouzadev)](https://github.com/vytorsouzadev/github-readme-stats)
- 👋 Hi, I’m @vytorsouzadev
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
vytorsouzadev/vytorsouzadev is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
.htaccess Redirecionar Todas as Rotas do Server Para o Arquivo .Html
<ifModule mod_rewrite.c>
    RewriteEngine On
    RewriteBase /
    RewriteCond %{REQUEST_FILENAME} !-f
    RewriteCond %{REQUEST_FILENAME} !-d
    RewriteRule (.*) /index.html [QSA,L]
</ifModule>
