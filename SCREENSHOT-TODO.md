# screenshot.png — TODO (do this after the repository is public)

`screenshot.png` is intentionally **absent** from this folder. The bounty
requires a screenshot of this repository's own page on GitHub, with the
README showing, taken once the repository is published. There is no public
repository yet and no screenshot was fabricated — a screenshot of anything
other than the real published page would be false, and the kit starter's
screenshot is a render of a sample repository that does not exist, so it
must not be copied in either.

## Before taking the screenshot

1. **Create the public repository.** It must be owned by the GitHub account
   linked to Udin's make.fun account (@leeminho), and created after the
   competition opened (18 Nov 2026, 10:30 UTC / 17:30 WIB). Suggested name:
   `make-fun-guide` (any name is fine — just use the real one everywhere
   below).
2. **Fix the badge placeholders in README.md.** The badge lines currently
   say `YOUR-GITHUB-USERNAME/make-fun-guide`. Replace
   `YOUR-GITHUB-USERNAME` with the real GitHub owner and `make-fun-guide`
   with the real repository name, so the rank and reward badges point at
   this repository. Commit and push.
3. **Push these files to the repository's default branch:** `README.md`,
   `LICENSE`, and (after this step) `screenshot.png`. Do not add a
   `.github/README.md` — GitHub would show that in place of the root README
   and the entry would be refused.
4. **Set the repository's About** (GitHub repo page → gear icon next to
   "About"): website `https://make.fun/bounty/bring-the-humans-02`, and add
   the topic `makefun`. Both are required by the `repo_about` check.
5. **Confirm the page renders:** open
   `https://github.com/<owner>/<repo>` while signed out (or in a private
   window) and check the README renders, the badges load, and the referral
   link `https://make.fun/r/wdbz3sg5` (code `wdbz3sg5`) is visible.

## How to take the screenshot

1. Open the repository's GitHub page in a desktop browser.
2. Scroll so the top of the capture shows the **repository name and the
   start of the README** — the board, the Feed, and the cards show a square
   cut from the top edge of the image, so the name and the guide's opening
   must be in that top square.
3. Take a full-page capture at normal scale (1x). A double-scale capture of
   a long page can exceed the pixel limit.
4. Save it as `screenshot.png` at the repository root (next to `README.md`).
5. Commit and push it before submitting.

## Limits the file must meet

- Format: PNG, JPEG, or WebP (this file is named `screenshot.png`, so PNG).
- Size: at most **8 MB**.
- Pixels: at most **16,000,000** (for example, 1280 px wide is fine; check
  with `python3 -c "from PIL import Image; print(Image.open('screenshot.png').size)"`
  or `file screenshot.png` and multiply width × height).
- Content: the repository's page on GitHub with the README showing.

## Checklist before submitting

- [ ] Repository is public, owned by the GitHub account linked to @leeminho
- [ ] Badge placeholders replaced with the real owner and repo name
- [ ] `README.md` at root names the referral code `wdbz3sg5`
- [ ] `LICENSE` (MIT) at root
- [ ] No `.github/README.md`
- [ ] About: website `https://make.fun/bounty/bring-the-humans-02`, topic `makefun`
- [ ] `screenshot.png` at root, ≤ 8 MB, ≤ 16,000,000 px, top shows repo name + start of README
- [ ] Transcripts of the agent sessions that built the guide bundled
      (`node cli/makefun.mjs bundle --repo <repo> --out transcripts.tar.gz`)
      and `check` run locally before submitting
