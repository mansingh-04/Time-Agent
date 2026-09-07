# TIME AGENT — Site Schedule Reconciliation Platform

**TIME AGENT** is the reconciliation layer between site execution and project schedule software (such as Primavera P6 or Microsoft Project).

---

## 🚀 Deploying to Vercel

### Option 1: Automatic Deployment via Vercel Dashboard (Recommended)

1. Commit and push your files to your GitHub repository:
   ```bash
   git add .
   git commit -m "Add Vercel deployment configuration and index.html"
   git push origin main
   ```
2. Go to [Vercel Dashboard](https://vercel.com/new).
3. Select your repository (`Time-Agent`) and click **Import**.
4. Leave the **Framework Preset** as **Other** (Static Site).
5. Click **Deploy**. Vercel will instantly host your app with SSL, CDN, and automatic updates on every push.

---

### Option 2: Deploy via Vercel CLI

Run the following command in your terminal inside the repository folder:

```bash
npx vercel
```

Follow the interactive prompts to deploy directly to your Vercel account. To deploy to production:

```bash
npx vercel --prod
```

---

## 💻 Local Development

To run and preview the application locally:

```bash
npm run dev
```

Or using `npx serve`:

```bash
npx serve .
```

Then open `http://localhost:3000` in your browser.

---

## 📁 Repository Structure

```
.
├── index.html            # Main web application entrypoint (served at /)
├── Time Agent.dc.html    # Original DC component source template
├── support.js            # DC framework runtime engine & logic handler
├── vercel.json           # Vercel deployment & routing configuration
├── package.json          # Development scripts and manifest
└── .gitignore            # Git ignore configuration
```
