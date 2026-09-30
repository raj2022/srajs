# Shivam Raj: personal website

Static site, no build step. Files: `index.html`, `photo.jpg`, and `cv.pdf` (you add this one).

## Add your CV

Compile your LaTeX CV to a PDF and save it as `cv.pdf` next to `index.html`.
The CV links in the nav, hero and contact section all point to that file name.
Consider making a web copy without your phone number, since the site is public.

## Publish

    cd /Users/sraj/Documents/Skills/website/srajs
    cp ~/Downloads/srajs-site/index.html ~/Downloads/srajs-site/photo.jpg .
    cp /path/to/your/CV.pdf cv.pdf
    git rm about.html achievements.html projects.html presentations.html styles.css \
           1659152301217.jpeg premium_photo-1682804227487-e8ffeb4b6ddd.avif \
           premium_photo-1682804227487-e8ffeb4b6ddd.png
    git add index.html photo.jpg cv.pdf
    git commit -m "Redesign homepage"
    git push
