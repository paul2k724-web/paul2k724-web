# Setup — Abraham Paul's Premium GitHub Profile

## 1. Create the profile repo
Create a **public** repo named exactly `paul2k724-web` (same as your username).

## 2. Drop these files in
```
paul2k724-web/
├── README.md
└── .github/
    └── workflows/
        └── snake.yml
```
Copy `README.md` and `.github/workflows/snake.yml` from this folder into that repo.

## 3. Enable Actions
- Go to **Settings → Actions → General**
- Under *Workflow permissions* select **Read and write permissions**
- Save

## 4. Run the snake once
- Go to **Actions → Generate Snake → Run workflow**
- Wait ~30 seconds. A new `output` branch appears with the SVGs.
- The README already points to that branch — the snake starts animating instantly.
- It auto-regenerates every 12 hours.

## 5. Optional polish
- Add a repo description: *"✨ My GitHub Profile — Abraham Paul Sanhith"*
- Pin your top 6 repos (Settings → Customize your pins).

Done. Your profile is live at https://github.com/paul2k724-web
