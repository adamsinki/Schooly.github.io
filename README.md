# Schooly Download Page

This is the landing page for the Schooly App.

## 🚀 How to Publish on GitHub

1.  **APK File**: Make sure you copy your app's APK file into this folder and rename it to `schooly.apk`.
    *   *Note: If your APK has a different name, edit line 33 in `Main.html` to match.*

2.  **Upload to GitHub**:
    *   Create a new repository on GitHub.
    *   Upload `Main.html`, `styles.css`, and `schooly.apk` to the repository.

3.  **Enable GitHub Pages**:
    *   Go to your repository **Settings**.
    *   Click on **Pages** in the left sidebar.
    *   Under "Build and deployment", select **Source** as `Deploy from a branch`.
    *   Select `main` (or `master`) branch.
    *   Click **Save**.

4.  **Important for Main.html**:
    *   By default, GitHub Pages looks for `index.html`.
    *   Since you are using `Main.html`, your website link will look like:
        `https://<your-username>.github.io/<repo-name>/Main.html`
    *   *Recommendation*: If you want the purely clean link (without `/Main.html`), you should rename `Main.html` back to `index.html`.

## 🎨 Customization

You can edit `styles.css` to change colors or animations.
