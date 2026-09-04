# Susmita Sett — GitHub Pages Website

A static academic/professional website ready for GitHub Pages.

## One thing to change before publishing

GitHub account usernames cannot contain spaces. The website currently contains this placeholder:

`susmitastro`

The site is already configured for the GitHub account `susmitastro`.

## Publish

1. Create a repository named `susmitastro.github.io`.
2. Upload all files and folders from this website folder to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`.
6. Save.

Your website will appear at `https://susmitastro.github.io`.

## Included

- Home / About
- Research interests
- Employment and research experience
- Education
- Publications
- Teaching, supervision and outreach
- Accepted telescope proposals
- Technical skills
- Contact
- Downloadable CV at `cv/Susmita_Sett_CV.pdf`

## Optional profile photo

Add a photo as `assets/profile.jpg`, then replace the initials element in `index.html` with:

```html
<img class="profile-photo" src="assets/profile.jpg" alt="Susmita Sett" />
```

and add:

```css
.profile-photo {
  width: 108px;
  height: 108px;
  object-fit: cover;
  border-radius: 50%;
  margin-bottom: 22px;
}
```
