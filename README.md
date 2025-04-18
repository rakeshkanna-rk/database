# 📁 Portfolio Data

This repository contains structured JSON files used to power the content of a personal portfolio website.  
It allows content to be updated remotely without rebuilding or deploying the frontend.

---

## 🌐 Live Data Usage

You can use raw file links to dynamically fetch data in your Vue or JavaScript apps.  
Example:

```js
fetch("https://raw.githubusercontent.com/<username>/database/main/portfolio/headLines.json")
  .then(res => res.json())
  .then(data => console.log(data));
```

---

## 🛠 How to Use Remotely in Vue

```js
const res = await fetch(
  "https://raw.githubusercontent.com/rakeshkanna-rk/database/main/portfolio/projects.json"
);
const projects = await res.json();
```

You can then pass the data to components or display it directly.

---

## 🔄 Benefits

- Update content without re-deploying your frontend
- Easily version-controlled and shareable
- Works well with GitHub Pages or any hosted frontend

---

## 💡 Tips

- Keep JSON clean and well-formatted
- Use `https://jsonlint.com/` for validation if needed
- Consider adding CI checks or formatting rules (e.g., Prettier)

---

## 📜 License

MIT — use freely for personal or commercial use.
```