# RePivot

**The internet, working intelligently for you.**

RePivot is a Mac browser that does the busywork of the web on your behalf — it
reads pages so you don't have to, keeps track of what you're actually trying to
get done, and reshapes what it finds into something you can use. It's built on
Chromium, so everything you expect from a browser still works.

## Download

Grab the latest build from the [**Releases**](https://github.com/jithendvG/repivot/releases/latest) page.

These are **dogfood builds** — early, rough around the edges, and improving fast.

## Opening RePivot on macOS (first launch)

The app is **signed** with a Developer ID but **not yet notarized** by Apple, so
the first time you open it macOS will warn you it "cannot verify the developer."
This is expected. To get past it:

1. Unzip the download and drag **RePivot.app** to your **Applications** folder.
2. **Right-click** (or Control-click) the app and choose **Open**.
3. In the dialog that appears, click **Open** again.

You only need to do this once — after the first launch it opens normally by
double-click.

> If you ever see "RePivot is damaged and can't be opened," it's the macOS
> quarantine flag. Right-click → Open as above, or run
> `xattr -dr com.apple.quarantine /Applications/RePivot.app` in Terminal.

## Reporting issues

Found a bug or something that felt wrong? Two ways to tell us:

Feedback from the app is collected privately — the in-app 👎 control files reports to the development tracker (screenshots and reports are never published here).
- **Here on GitHub:** [open an issue](https://github.com/jithendvG/repivot/issues/new) directly.

Concrete details help most: what you were doing, what you expected, and what
happened instead.

## About the code

RePivot's source is **currently private**. This repository is the public home
for **downloads and issue tracking** while the product is in early access.
