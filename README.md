# AI &amp; Cloud Reference Architectures — Jeremiah Kim

A portfolio of enterprise AI and cloud reference architectures (cloud-agnostic, generalized).
This folder is a complete, self-contained static site — `index.html` plus the diagram images.

---

## Publish on GitHub Pages (about 5 minutes)

1. **Create a new public repository** on GitHub — e.g. `ai-reference-architectures`.
2. **Upload these files into the repository root.** In the repo, click **Add file → Upload files**,
   then drag in `index.html` **and all seven `.png` files** together, and commit.
   *(Keep `index.html` and the PNGs in the same folder — the page loads the images by filename.)*
3. Go to **Settings → Pages**. Under **Build and deployment**:
   - **Source:** Deploy from a branch
   - **Branch:** `main` and folder `/ (root)` → **Save**
4. Wait about a minute. Your site goes live at:
   `https://<your-username>.github.io/<repository-name>/`
5. Put that URL on your resume as a **clickable hyperlink**
   (and in your LinkedIn *Featured* section).

---

## Optional: use your own domain

If you own **njrcloud.com**, you can serve this at something like `architecture.njrcloud.com`:

1. **Settings → Pages → Custom domain** → enter `architecture.njrcloud.com` → Save.
2. At your DNS provider, add a **CNAME** record:
   `architecture`  →  `<your-username>.github.io`
3. GitHub provisions HTTPS automatically (tick **Enforce HTTPS** once it appears).

A custom domain looks more professional on a resume and is easy to remember.

---

## Editing the page

Open `index.html` in any text editor:

- Update your **name, title, intro, and contact links** at the top
  (replace the `REPLACE-ME` LinkedIn/GitHub URLs; the email is already set).
- Edit any **diagram title or description** inside its `<article>` block.
- To **add or remove a diagram**, copy an existing `<article>…</article>` block,
  drop the new image file into the same folder, and update the filename, title, and text.

No build step, no frameworks, no dependencies — it is plain HTML and CSS.
