# lechovia-skies.github.io

The way in to **Lechovia Skies**, the browser jet-combat game. The game itself is the repository
[`lechovia-skies/._.`](https://github.com/lechovia-skies/._.), served at **https://lechovia-skies.github.io/._./**.

This repository is the organization's GitHub Pages site, so it answers every other address on
`lechovia-skies.github.io` and sends the visitor on to the game:

- `index.html`: the bare address https://lechovia-skies.github.io/ (with a link preview for chat apps).
- `404.html`: any address with nothing behind it. Chat apps drop the last `.` of a link that ends in `/._.`, so a
  link sent without its final `/` opens `/._` and used to show GitHub's 404 page. Old addresses such as
  `/lechovia-sky/` and typos land here too.

GitHub Pages publishes it from the `main` branch (Settings → Pages: Deploy from a branch, `main`, `/ (root)`).
