# LuLu's Time Check — GitHub Pages support site

A standalone static support and privacy-policy site for the Apple Watch app.

## Publish

1. Make a **public** GitHub repository (e.g. `lulus-time-check-support`).
2. Upload `index.html`, `privacy.html`, and `app-icon.png` to the repository root; also include `.nojekyll` if you'd like.
3. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, branch **main**, folder **/(root)**, and Save.
4. Wait until GitHub shows the published site URL, then open the actual URL in a private window and test links and the contact form.
5. In App Store Connect use the **actual URL GitHub reports** (do not just assume this example matches your username):
   - Support URL: `https://YOUR-GITHUB-USERNAME.github.io/lulus-time-check-support/`
   - Privacy Policy URL: `https://YOUR-GITHUB-USERNAME.github.io/lulus-time-check-support/privacy.html`

## Before publishing
- Confirm that the external Camp Chair Studios website's contact form works and is the support contact you intend to use.
- Check that the site's statements still match the submitted app build.
- GitHub Pages requires a public repository when you are using a Free plan.
- These files are not live until deployed; App Store Connect needs public working URLs.
