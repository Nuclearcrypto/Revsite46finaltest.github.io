
# Rev-N-Rip Embedded GitHub Site

This package is built to avoid broken image links and the white-page / black-text issue.

## What makes this version safer
- Every page is self-contained.
- CSS is embedded directly in each HTML file.
- JavaScript is embedded directly in each HTML file.
- Background images are embedded directly in code as data URLs.
- No assets folder is required.
- No external CSS or framework dependencies are required.

## Files included
- index.html
- marketplace.html
- breaks.html
- syndicate.html
- concierge.html
- .nojekyll

## Important edit
Search all files for:
YOUR-EMAIL@example.com
and replace it with your real email address.

## Primary store link
All major CTAs point to:
https://www.ebay.com/str/metazooinvestorssociety

## GitHub upload steps
1. Upload all files in this ZIP to the root of your GitHub repository.
2. Make sure the root contains index.html and .nojekyll.
3. In GitHub: Settings -> Pages -> Deploy from a branch -> main -> /(root)
4. Save and wait a minute or two.

## If GitHub still shows an older version
Visit the site once with a cache-busting query string, such as:
?v=2


## Update
Added a safe hide script for the Vault + Grail Garage button. The rest of the site was left untouched. To bring it back later, remove the small script marked 'Hidden for later: Vault + Grail Garage button' before the closing body tag in each HTML file.


## eBay store link update
- Store links now point to: https://www.ebay.com/str/metazooinvestorssociety
- Store-facing buttons now say: Visit Ebay Store
- This build is based on the reset baseline: Vault + Grail Garage hidden.
