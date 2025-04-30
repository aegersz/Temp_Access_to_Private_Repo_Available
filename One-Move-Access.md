# ✅ One-Move-Access.md  
*Granting GitHub Private Repo Access in One Quick Move*

---

## 🚀 Web Interface (Fastest Method)

1. Go to your private repository on GitHub  
2. Click **Settings** → **Manage Access** *(or use direct link below)*  
3. Click **“Invite a collaborator”**  
4. Enter their **GitHub username**  
5. Click **“Add”** — you're done! ✅

> 📬 The user will receive an invite via GitHub + email. They must **accept** it before accessing the repo.

---

## 🔗 Direct Access Shortcut

Paste this in your browser (edit to match your repo):

```
https://github.com/OWNER/REPO/settings/access
```

Replace `OWNER` and `REPO` with your actual GitHub username and repository name.

---

## 🖥️ Optional: GitHub CLI Method

If you're using the GitHub CLI (`gh`), you can run:

```
gh repo add-collaborator OWNER/REPO --user USERNAME --permission read
```

> Example:  
> `gh repo add-collaborator aegersz/Neuropharmacoescapades --user trustedResearcher --permission read`

---

## 🛡️ Best Practices

- Use **read-only** unless code contribution is needed  
- Remove users anytime from **Settings → Manage Access**  
- Keep sensitive data in `.gitignore` or protected branches

---

**One move. One invite. Total control.**  
Stay sharp — stay selective.  
— *Andrew and AI -- AEnAI preferred ...*

---
