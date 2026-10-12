# How to publish your GitHub CV profile

Your profile README shows on the top of your GitHub profile page (github.com/Aman8401) once it lives in a special repository named exactly like your username.

## 1. Create the profile repository
1. Sign in to GitHub and open https://github.com/new
2. Repository name: **Aman8401** (must match your username exactly)
3. Choose **Public**
4. Do **not** tick "Add a README" (we already have one)
5. Click **Create repository**

## 2. Upload the README and the animations
On the new empty repository page:
1. Click **uploading an existing file**
2. Drag in **both** `README.md` **and the whole `assets` folder** from this folder (drag the folder itself, so the files stay inside `assets/`)
3. Click **Commit changes**

The `assets` folder holds the animated header, stats tiles, project cards and "currently building" card. Without it those images show as broken.

Open https://github.com/Aman8401 and the profile appears.

## 3. Turn on the snake animation (optional, 2 minutes)
The "snake eating your contributions" animation needs a small GitHub Action.

1. In the **Aman8401** repository, click **Add file → Create new file**
2. File name: `.github/workflows/snake.yml`
3. Paste everything from `snake-workflow.yml` (in this folder)
4. Click **Commit changes**
5. Go to **Settings → Actions → General → Workflow permissions**, choose **Read and write permissions**, then **Save**
6. Go to the **Actions** tab → **Generate contribution snake** → **Run workflow**

After about a minute the snake appears at the bottom of your profile and refreshes every day.

## 4. Use a different username?
LinkedIn and HackerRank links use `amansp`. If those usernames are different, open `README.md` and change them.

## 5. Share it
Your shareable CV link is:

**https://github.com/Aman8401**

Add it to your LinkedIn, email signature and resume.
