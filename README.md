# Shivam Raj: personal website

Static site, no build step. Files: `index.html`, `photo.jpg`, `cv.pdf`, and the `fonts/` folder.

The fonts (STIX Two Text and Hanken Grotesk, both open-licensed) are included so the
site does not depend on Google. Keep the `fonts/` folder next to `index.html`.

## Publish

    cd /Users/sraj/Documents/Skills/website/srajs
    cp ~/Downloads/srajs-site/index.html .
    cp -r ~/Downloads/srajs-site/fonts .
    git add index.html fonts
    git commit -m "New page architecture"
    git push

`cv.pdf` and `photo.jpg` are already in your repo and do not change.
