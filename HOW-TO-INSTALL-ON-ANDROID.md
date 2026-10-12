# Cut Plan on your Android phone

The app is the `app/` folder (5 files). It has four tabs:

- **Train**: opens on today's workout. Each exercise has an animated demo and Set 1/2/3 buttons you tap as you go. Ticks reset each day.
- **Diet**: daily targets, the Day A and Day B menus, protein cost, and where calories leak.
- **Rules**: weekly adjustment rules, progression ladders, what to track.
- **Plan**: timeline, blood tests, supplements, regain plan, and why v2 changed things.

---

## Option 1: Installable app, works offline (recommended)

This folder lives in your personal GitHub repo `Saifulhuq01/gym_training`. Turn on the website once:

1. On github.com, open the repo and go to **Settings → Pages**.
2. Under "Branch", choose `main` and `/ (root)`, then click **Save**.
3. Wait 1–2 minutes. The app's address is **https://saifulhuq01.github.io/gym_training/app/**
4. Open that address in **Chrome on your phone**. Tap **⋮ → Install app**. On some phones it says **Add to Home screen**.

Now you have a "Cut Plan" icon on your home screen. It opens full screen and works without internet after the first open.

**Privacy:** free GitHub Pages needs a public repo, so anyone with the link can see these files. That includes your weight numbers and, in `mohammed-cut-plan.html`, your first name.

**Updating later:** after changing `app/index.html`, change `cutplan-v1` to `cutplan-v2` in `app/sw.js`, then commit and push. Phones pick up the new version the next time they open the app online.

---

## Option 2: Copy the single file to your phone (no account)

1. Send `app/index.html` to your phone, for example by USB cable, Google Drive, or a message to yourself.
2. Open it with **Chrome**. In the Files app, tap the file and choose **Open with → Chrome**.

The file contains everything it needs and works offline. Your set ticks are saved in Chrome. It won't have a home-screen app icon, and some Android file managers make opening local HTML files awkward. If yours does, use Option 1 or 3.

---

## Option 3: Private link (no setup, needs internet)

Open https://claude.ai/artifact/4uJgBvqa4cAEovaQjxE9u3 in Chrome on your phone. Sign in to the same Claude account, then tap **⋮ → Add to Home screen**.

The link stays private to your account. It needs internet and a signed-in Claude account, and it opens as a web page, not a full-screen app.
