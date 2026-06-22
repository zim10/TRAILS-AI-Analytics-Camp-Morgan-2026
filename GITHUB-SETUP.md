# How to Set Up This Repository on GitHub

A quick guide for administrators and collaborators.

---

## Step 1: Create the Repository

1. Go to [github.com](https://github.com) and log in to your **personal account**
2. Click the **"+"** icon → **New repository**
3. Name it something like: `TRAILS-AI-Analytics-Camp-Morgan-2026` or `ai-workshop-baltimore`
4. Set visibility to **Public** (so students, partners, and TRAILS can see it)
5. Check **"Add a README file"** (you'll replace it with our README)
6. Click **Create repository**

---

## Step 2: Add Your University Email to GitHub

You do **not** need a separate GitHub account for your university email. Instead:

1. Log in to GitHub with your personal account
2. Go to **Settings** (top-right profile menu)
3. Click **Emails** in the left sidebar
4. Click **Add email address** and enter your `@morgan.edu` email
5. Check your university inbox and **verify the email**

Now both emails are linked to the same account. You can choose which email appears on your commits.

---

## Step 3: Upload These Files

**Option A — GitHub Web Interface (easiest):**
1. In your new repo, click **"uploading an existing file"**
2. Drag and drop all folders and files
3. Write a commit message like: `Initial commit — workshop materials`
4. Click **Commit changes**

**Option B — Git Command Line:**
```bash
git clone https://github.com/YOUR-USERNAME/TRAILS-AI-Analytics-Camp-Morgan-2026.git
cd TRAILS-AI-Analytics-Camp-Morgan-2026
# Copy all files into this folder
git add .
git commit -m "Initial commit — workshop materials"
git push origin main
```

---

## Step 4: Invite Collaborators (Optional)

To let other faculty or staff contribute:
1. Go to **Settings → Collaborators**
2. Click **Add people**
3. Enter their GitHub username or email

---

## Step 5: Make It Look Good

- Pin the repo to your GitHub profile
- Add a short **Description** and relevant **Topics** (e.g., `ai`, `education`, `baltimore`, `morgan-state`)
- Add a **Website** link if you have a program page

---

## Repository Permissions Summary

| Who | Access Level |
|-----|-------------|
| Program Coordinator | Admin (owner) |
| Co-facilitating Faculty | Write (collaborator) |
| Student Mentors | Read (or Write if contributing) |
| Public (students, partners, TRAILS) | Read (public repo) |

---

*For questions about GitHub setup, contact your program coordinator or IT support at Morgan State.*
