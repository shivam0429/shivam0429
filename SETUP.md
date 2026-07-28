# Setup Instructions

## 1. Create the profile repository

Create a new public GitHub repository named exactly:

```text
shivam0429
```

The final repository path must be:

```text
shivam0429/shivam0429
```

Initialize it with a README.

## 2. Upload this package

Upload the following items to the repository root:

- `README.md`
- `assets/`
- `.github/`

Commit the files to the `main` branch.

## 3. Enable the contribution-snake workflow

Open the profile repository, then go to:

**Settings → Actions → General → Workflow permissions**

Select:

**Read and write permissions**

Save the setting.

Then open:

**Actions → Generate Snake Animation → Run workflow**

Wait until the workflow is green. It will create the `output` branch automatically.

## 4. Add your GitHub profile details

Go to your GitHub profile and select **Edit profile**.

Recommended values:

- Name: `Shivam Singh`
- Bio: `Full Stack Developer | React • Node.js • Flask • Python | Building real-world applications`
- Location: `Delhi, India`
- LinkedIn: `https://www.linkedin.com/in/shivamsingh29`

## 5. Optional: self-host GitHub Readme Stats

The README currently uses the public GitHub Readme Stats service. It works, but it may occasionally hit rate limits.

For more reliable cards:

1. Fork `anuraghazra/github-readme-stats`.
2. Create a GitHub classic personal access token.
3. Import the fork into Vercel.
4. Add the token in Vercel as `PAT_1`.
5. Deploy the project.
6. Replace `https://github-readme-stats.vercel.app` in `README.md` with your own Vercel deployment URL.

Never put your GitHub token inside the README or any public repository.

## 6. Recommended pinned repositories

Pin these repositories:

1. Hospital Management System
2. Chat App
3. AI-Powered CRM
4. Task Tracker

Add two more when your portfolio and e-commerce repositories are ready.
