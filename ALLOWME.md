# 🔐 ALLOWME.md  
*Granting Temporary Access to a Private GitHub Repository*

---

## ✅ Steps to Allow Access (One User Only)

1. Go to your **private repository** on GitHub.
2. Click the **“Settings”** tab at the top.
3. Scroll down the left sidebar and select **“Collaborators and teams”** under “Access”.
4. Under the **Collaborators** section, click **“Add people”**.
5. Type the GitHub **username** of the user you wish to invite.
6. Click **“Add [username] to this repository”**.
7. Choose the appropriate **permission level**:
   - `Read` → View-only access (**recommended**)
   - `Triage` → Can manage issues and pull requests
   - `Write` → Can commit code
   - `Admin` → Full control (**not advised unless trusted**)

---

## 🧭 Notes on Access Control

- Invited users must **accept the invitation** before access becomes active.
- Access can be **revoked at any time** through the same “Collaborators” settings page.
- You may track activity through the repository's **“Insights → Contributors”** panel.

---

## 🛡️ Recommended Permission: `Read`

This grants:
- Clone/view code
- Read issues, discussions, and pull requests
- No ability to modify, delete, or push changes

---

## 📩 Optional: DM Template for Sending Access

> "Hi [Username],  
> I've granted you temporary **read-only** access to the Neuropharmacoescapades repo for research/review purposes. Please accept the invite from GitHub when you see it. Let me know if you have any questions or want to coordinate a time-limited session.  
> — Andrew"

---

## 🧨 Want More Control?

Consider using:
- **GitHub Actions** to auto-revoke access after X days  
- **Branch protection rules** to lock sensitive files  
- A **public stub repo** (like this one) to manage access requests

---

**Use this power wisely. Trust is like dopamine — amazing until abused.**  
— *AEnAI* (or Andrew E aNd Artificial Intelligence)

---

