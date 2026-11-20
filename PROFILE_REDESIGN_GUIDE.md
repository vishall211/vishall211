# 🚀 GitHub Profile Redesign Blueprint for @vishall211

This blueprint covers how engineers and tech leaders configure their GitHub presence to attract recruiters, engineering managers, and collaborators.

---

## 📋 The 5-Pillar Professional Transformation

```
┌────────────────────────────────────────────────────────┐
│  1. Profile Identity (Avatar, Bio, Pronouns, Links)   │
├────────────────────────────────────────────────────────┤
│  2. Profile README (vishall211/vishall211)             │
├────────────────────────────────────────────────────────┤
│  3. Pinned Repositories Showcase                       │
├────────────────────────────────────────────────────────┤
│  4. Contribution Graph & Public Activity               │
├────────────────────────────────────────────────────────┤
│  5. Individual Repository Polish (Topics, Clean Docs)  │
└────────────────────────────────────────────────────────┘
```

---

## Step 1: Create the Special Profile Repository

GitHub provides a special feature: when you create a public repository with the exact same name as your username (`vishall211/vishall211`), the `README.md` in that repository will be displayed on your main profile overview!

1. Go to [https://github.com/new](https://github.com/new).
2. Set **Repository name** to: `vishall211`.
3. Set visibility to **Public**.
4. Check **Add a README file**.
5. Click **Create repository**.
6. Replace the repository's `README.md` content with the code from [`README.md`](file:///Users/vishalsingh/Desktop/Projects%202026/GitHub%20redesign/README.md).

---

## Step 2: Unlock Your Contribution Graph (Fix "Activity is private")

Right now, your profile displays:
> *@vishall211's activity is private*

This prevents visitors from seeing your continuous coding streaks and consistency.

### How to Fix:
1. Go to your GitHub profile overview: [https://github.com/vishall211](https://github.com/vishall211).
2. In the contribution calendar section or in your [Account Settings](https://github.com/settings/profile):
   - Navigate to **Settings** → **Public profile** → **Contribution settings**.
   - Check **"Include private contributions on my profile"**.
   - Ensure your profile visibility settings allow public activity.
3. Verify your Git email locally: Ensure commits made from your computer match the email verified on GitHub (`git config user.email` matches an email under [GitHub Email Settings](https://github.com/settings/emails)), so all your commits receive proper attribution.

---

## Step 3: Polish Sidebar Profile & Bio

### Current vs Recommended Bio:

* **Current Bio:**
  > `Data enthusiast focused on analytics, problem solving, and building tools that turn raw data into decisions. Currently strengthening DSA and system thinking.`

* **Recommended Professional Bio (Choose one, fits within GitHub's 160-char limit):**
  - **Option A (Systems & ML Focus):**
    > `Data Science & ML Engineer | Building DTUMOS & Multimodal AI | Turning complex transit & sensor data into predictive systems.`
  - **Option B (Impact & Product Focus):**
    > `Machine Learning & Analytics | Ex-Data Science Intern @ Sabudh | Building real-time predictive models & multimodal AI apps.`

### Sidebar Fields:
- **Name:** Vishal Singh
- **Company:** Sabudh Foundation (or open to roles: *Open to Data Science / ML Roles*)
- **Location:** Chandigarh, India
- **Website:** `https://vishalx.vercel.app`
- **Social accounts:**
  - LinkedIn: `https://www.linkedin.com/in/vishall211/`
  - LeetCode / HackerRank: Linked in your profile README.

---

## Step 4: Pin Your Top 3 Repositories

Instead of letting GitHub auto-show or hide repositories, explicitly pin your strongest projects:

1. On your profile page, click **Customize your pins** (or **Edit pins**).
2. Select these 3 repositories:
   1. **`DTUMOS`**: Highlight of predictive modeling, transit data, and Python data science.
   2. **`Vibe-Storytelling`**: Demonstrates full-stack multimodal AI product engineering with Flutter/Dart.
   3. **`Sabudh-2026`**: Demonstrates industry internship rigor and data science fundamentals.

---

## Step 5: Repository Hygiene (How Pros Make Repos Look Production-Ready)

For each pinned repository, follow these standards:

### 1. Add Repository Topics (Tags)
On each repo homepage, click the gear icon ⚙️ next to "About":
- For **`DTUMOS`**:
  `digital-twin`, `urban-mobility`, `machine-learning`, `transit-data`, `spatial-analytics`, `python`, `predictive-modeling`
- For **`Vibe-Storytelling`**:
  `generative-ai`, `multimodal`, `flutter`, `dart`, `ai-storyteller`, `text-to-speech`, `ghibli-style`
- For **`Sabudh-2026`**:
  `data-science`, `machine-learning`, `internship`, `data-analytics`, `algorithms`, `eda`

### 2. Set the "About" Website / Demo link
- For `Vibe-Storytelling`, add a link to an APK release, demo video, or portfolio writeup.
- For `DTUMOS`, add a link to the research report, notebook, or web dashboard if available.

### 3. Ensure a Standard Repository README Structure
Every professional repository includes:
- **Badges**: Python version, license, build status.
- **Problem Statement**: What problem does this solve?
- **Architecture / Methodology**: How the data flows or how the AI is integrated.
- **Quickstart**: Reproducible setup instructions (`pip install -r requirements.txt`, `python run.py`).
- **Results / Metrics**: Accuracy, latency, sample screenshots, or sample output.

