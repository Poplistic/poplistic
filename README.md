<p align="center">
  <img src="me.png" alt="Poplistic Logo" width="120" />
</p>

<h1 align="center">Poplistic Readme Stats 📊</h1>

<p align="center">
  A fork of the popular GitHub README stats generator that lets you display dynamic GitHub metrics — 
  like most used languages — with customizable themes and layouts. Powered by Vercel and SVG magic! :contentReference[oaicite:0]{index=0}
</p>

---

## 📈 Stats at a Glance

<p align="center">
  <!-- GitHub Profile Stats -->
  <img 
    src="https://poplistic-readme.vercel.app/api?username=Poplistic&show_icons=true&theme=dark&hide_border=true"
    alt="GitHub Stats"
    width="450"
  />

  <!-- Top Languages Card -->
  <img
    src="https://poplistic-readme.vercel.app/api/top-langs/?username=Poplistic&layout=compact&theme=dark&langs_count=10&hide_border=true"
    alt="Top Languages"
    width="450"
  />
</p>

---

## 🚀 About This Project

**Poplistic Readme Stats** is designed to help developers and open-source contributors showcase their GitHub activity and language usage directly in their profile README using dynamic SVG cards.  
You can create cards like:

- ⭐ Total GitHub stats (stars, commits, followers) :contentReference[oaicite:1]{index=1}  
- 🧠 Top languages used across your repositories :contentReference[oaicite:2]{index=2}  
- 📌 Repository / pin cards  
- 🕒 Streaks and WakaTime integrations (if added)

*(All cards are customizable using URL parameters for themes, layout, colors, and more.)*

---

## 🔧 How to Use

Just add the following snippet to your own `README.md`:

### 💡 GitHub Stats Card

```markdown
![GitHub Stats](https://poplistic-readme.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=dark)
