# HKL Pathology Portal - Landing Page

This is the **landing page** for the HKL Pathology Portal.\
It serves as a central hub (similar to Linktree/Beacons style) with
quick access to important resources like the **Pathology Test
Directory**, posters, videos, and learning materials.

------------------------------------------------------------------------

## 🌐 Features

-   Clean & modern **responsive design** (desktop & mobile friendly).
-   Hero section with logo, title, and tagline.
-   Card-style links with hover animation.
-   Simple to customize (logo, title, tagline, and links).

------------------------------------------------------------------------

## 🛠️ How to Customize

### 1. Logo

Find this line in the HTML:

``` html
<img src="https://via.placeholder.com/100" alt="HKL Logo" />
```

Replace the `src` with your logo URL (e.g. Google Drive direct link,
Imgur, or local file).

------------------------------------------------------------------------

### 2. Title & Tagline

``` html
<h1>HKL Pathology Portal</h1>
<p>Quick access to tests, materials & resources</p>
```

Change the `<h1>` for the main title, and `<p>` for the tagline.

------------------------------------------------------------------------

### 3. Links

``` html
<a class="link-card" href="test-directory.html" target="_blank">🔬 Pathology Test Directory</a>
```

-   Replace `href` with the URL to your resource.\
-   Edit the text between `<a>...</a>` to update the button label.

------------------------------------------------------------------------

## 📂 File Structure

    index.html     # Main landing page file
    README.md      # This file (instructions & documentation)

------------------------------------------------------------------------

## 🚀 Deployment

1.  Host the `index.html` file on any static site hosting service:
    -   GitHub Pages
    -   Netlify
    -   Vercel
    -   Or serve directly from local server
2.  Share the landing page URL with users.

------------------------------------------------------------------------

## 👨‍💻 Credits

Designed by **Fahim Hamdan** ✨
