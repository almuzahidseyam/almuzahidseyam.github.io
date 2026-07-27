# almuzahidseyam.github.io — LinkedIn-ready gateway

This package replaces the zero-second redirect with a public, crawlable portfolio gateway. The detailed Firebase portfolio remains private and opens only after the visitor clicks the button.

## Publish

1. Open the `almuzahidseyam.github.io` repository.
2. Delete the old redirect files from the repository root.
3. Upload every file and the `assets` folder from this package to the repository root.
4. Commit the changes.
5. In **Settings → Pages**, use `main` and `/ (root)`.
6. Wait for the Pages deployment to finish.

## Refresh LinkedIn

1. Open LinkedIn Post Inspector.
2. Inspect `https://almuzahidseyam.github.io/`.
3. Confirm that the title, description, and 1200×627 preview image appear.
4. Return to Profile → Featured → Add a link and enter the same URL.

Do not restore the old zero-second meta refresh or `noindex,nofollow` tag; either can prevent social crawlers from validating the page.
