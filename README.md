# 📁 Portfolio Data

This repository contains structured JSON files used to power the content of a personal portfolio website.  
It allows content to be updated remotely without rebuilding or deploying the frontend.

---

## 🌐 Live Data Usage

You can use raw file links to dynamically fetch data in your Vue or JavaScript apps.  
Example:

```js
fetch(
  "https://raw.githubusercontent.com/<username>/database/main/portfolio/headLines.json"
)
  .then((res) => res.json())
  .then((data) => console.log(data));
```

---

## 🛠 How to Use Remotely in Vue

```js
const res = await fetch(
  "https://rakeshkanna-rk.github.io/database/portfolio/projects.json"
);
const projects = await res.json();
```

You can then pass the data to components or display it directly.

## Database

### Portfolio Links

- [Projects Code](https://rakeshkanna-rk.github.io/database/portfolio/codeProjects.json)
- [Projects Design](https://rakeshkanna-rk.github.io/database/portfolio/designProjects.json)
- [Projects Home](https://rakeshkanna-rk.github.io/database/portfolio/homeProjects.json)
- [Timeline](https://rakeshkanna-rk.github.io/database/portfolio/timeline.json)
- [Tech Stack](https://rakeshkanna-rk.github.io/database/portfolio/TechStack.json)
- [Links](https://rakeshkanna-rk.github.io/database/portfolio/links.json)
- [Freebies](https://rakeshkanna-rk.github.io/database/portfolio/freebies.json)
- [Feedback](https://rakeshkanna-rk.github.io/database/portfolio/feedback.json)

---

### YT Learns

- [Topics](https://rakeshkanna-rk.github.io/database/YT-Learns/topics.json)
- [Frontend](https://rakeshkanna-rk.github.io/database/YT-Learns/topics/frontend.json)
- [Backend](https://rakeshkanna-rk.github.io/database/YT-Learns/topics/backend.json)
- [Database](https://rakeshkanna-rk.github.io/database/YT-Learns/topics/database.json)
- [DevOps](https://rakeshkanna-rk.github.io/database/YT-Learns/topics/devops.json)

### Common

- [Image Placeholder](https://rakeshkanna-rk.github.io/database/img/img_placeholder.png)

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

```
