# 📄 Updating the Documentation

This guide explains how to update, add, or style pages on our Mintlify-powered documentation site.

---

## 1. Updating Existing Page Content

All page content lives in the **`introduction/`** directory of this repository.

To update a page:
1. Navigate to the `introduction/` folder
2. Find the `.mdx` file that corresponds to the page you want to edit
3. Make your changes directly in the file
4. Save and proceed to [Step 3](#3-push-changes-to-the-main-repo)

---

## 2. Adding a New Page or Styling

For adding new pages, configuring navigation, or applying custom styling, refer to the official Mintlify documentation:

🔗 [Mintlify Docs](https://www.mintlify.com/docs)

Key things you can do there:
- Add new `.mdx` pages and register them in `mint.json`
- Customize colors, fonts, and logos
- Configure navigation groups and tabs
- Use built-in components (callouts, cards, code blocks, etc.)

---

## 3. Push Changes to the Main Repo

Once your edits are ready, push them to the `main` branch:

```bash
git add .
git commit -m "docs: describe your changes here"
git push origin main
```

> ⚠️ Changes only go live after syncing in the Mintlify dashboard (see Step 5).

---

## 4. Log In to the Mintlify Dashboard

Go to the Mintlify dashboard and sign in:

🔗 [https://dashboard.mintlify.com/login](https://dashboard.mintlify.com/login)

---

## 5. Sync Manually

After pushing your changes and logging in:

1. Navigate to your project in the dashboard
2. Click **"Sync manually"**
3. Wait for the sync to complete — your updates will be live shortly after

---

## Quick Reference

| Task | Where |
|------|--------|
| Edit existing content | `introduction/` directory |
| Add pages / styling | [Mintlify Docs](https://www.mintlify.com/docs) |
| Push updates | `git push origin main` |
| Trigger deployment | [Mintlify Dashboard](https://dashboard.mintlify.com/login) → Sync manually |
