# Surrey Opticians Secret Santa 🎅

A one-page Secret Santa app you can share. It's open source (MIT) and has no logins, no database and no tracking.

- **You (the organiser)** open the page, check the names, set the spend limit and date, then tap **Draw names**.
- You get one **WhatsApp** button per person. Tap it, pick that person's chat and send.
- **They** open the link, confirm it's them, tap the present and see who they're buying for.
- **You never see the matches.** The page doesn't show them to you, and it doesn't keep them anywhere.

## Put it online (free, about 5 minutes)

The links have to point at a public copy of `index.html`. Otherwise they won't open on anyone's phone. Pick one of these:

### Option A: GitHub Pages (permanent, free)
1. Sign in at github.com (or create a free account). Only you need an account. The people you send links to don't.
2. Click **New repository**, name it `secret-santa`, set it to **Public** and create it.
3. Click **uploading an existing file**, drag in `index.html` (and this README if you like), then **Commit**.
4. Go to **Settings → Pages**. Under *Branch*, choose `main` / `(root)` and **Save**.
5. After about a minute your page is live at `https://<your-username>.github.io/secret-santa/`.

### Option B: Netlify Drop
1. Go to app.netlify.com/drop, put `index.html` in a folder and drag the folder onto the page.
2. Create the free account it asks for so the site doesn't expire.
3. You'll get an address like `https://something.netlify.app`.

## Run the draw
1. Open **your hosted address** (not the file on your computer).
2. Check the names. Spend limit and gift-exchange details are optional.
3. Optionally list pairs who shouldn't draw each other (one pair per line, like `Andy, Ben`).
4. Tap **Draw names**, then send each person's link with the **WhatsApp** button. Ticks show who you've done.
5. The draw is saved in that browser, so you can close it and come back to finish. **Start again & redraw** makes a brand-new draw, and you'd then need to resend every link.

## How the privacy works
Each person's match is scrambled into the part of the link after `#`. Browsers never send that part to the web server, so the host never sees it. The organiser screen only shows names and buttons.

The scrambling is enough for an office Secret Santa but it isn't bank-grade encryption. Someone determined and technical could decode a link they were given, so ask people not to forward theirs.
