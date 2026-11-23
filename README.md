# GitHub Pages collection

Each folder contains a standalone page and its Facebook link preview. The root `index.html` lists the sample pages.

## Publish on GitHub Pages

1. Create a GitHub repository and push these files to its default branch. A public repository works with GitHub Free.
2. In the repository's **Settings → Pages**, choose **Deploy from a branch**, select the branch you pushed to (usually `main`), and select **/ (root)**. Save.
3. Replace the example `og:url` and `og:image` addresses in each page with the live HTTPS addresses shown by GitHub Pages, then push the changes. The examples assume the repository is named `facebook_pages`.

The URL for `first-page/index.html` is `https://YOUR-USERNAME.github.io/facebook_pages/first-page/`. Use the folder URL when sharing. The empty `.nojekyll` file tells GitHub Pages to serve the static files as-is.

[GitHub Pages publishing instructions](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

## Add and share a page

1. Copy `first-page/` to a folder with a new name, such as `garden-notes/`.
2. Edit its `index.html`. Update the page title and content, the Open Graph title and description, and the absolute `og:url` and `og:image` URLs. Add a link in the collection's root `index.html` if you want the page listed there.
3. Replace `share.png` with your own preview image. A 1200 × 630 PNG or JPEG is a good starting point. If you start with an SVG, export it as a PNG or JPEG for the Facebook preview. The sample folders include editable SVGs and their PNG exports. If you change the filename or dimensions, update the corresponding image tags and alt text.
4. Push your changes. Once the page is live, paste its URL into a Facebook post and let Facebook build the clickable preview from the page's Open Graph tags. Use Meta's Sharing Debugger to inspect it or select **Scrape Again** after updating a preview.

[Meta's sharing guide](https://developers.facebook.com/documentation/sharing/webmasters) · [Facebook Sharing Debugger](https://developers.facebook.com/tools/debug/)
