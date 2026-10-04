# Art From The Heart — Tanya Moiseev

A static, GitHub Pages-ready art gallery website.

## Files

- `index.html` — complete gallery website
- `images/` — thumbnail and large artwork images

## Replace the sample artwork

Each artwork uses two files with matching numbers:

- `art01-thumb.jpg` — small gallery thumbnail
- `art01-large.jpg` — larger image opened when clicked

Continue the same pattern for `art02`, `art03`, etc.

The easiest approach is to resize Tanya's original paintings into:

- thumbnails: about 700 × 525 px
- large images: about 1600 × 1200 px

Then overwrite the sample JPG files while keeping the same filenames.

## Publish on GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` and the entire `images` folder to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)` folder, then save.
6. GitHub will provide your public gallery URL.

## Add more paintings

Duplicate one `.art-card` block inside the `#galleryGrid` element in `index.html`, then update:

- `data-large`
- `data-title`
- thumbnail `src`
- image `alt`
- visible artwork title and number



## Artwork details
Each gallery card in `index.html` includes editable `data-title`, `data-medium`, and `data-price` values. Update those values and the visible title/medium/price text for Tanya’s actual works.
