# Pilea Studio

A lightweight static site for Pilea Studio, an independent app development studio in Torquay, Victoria.

The vector brand mark is stored in `logo-mark.svg`, with the browser icon in `favicon.svg`.

## Local preview

Run a simple local server from the repository root:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages

In the repository settings, open **Pages**, choose **Deploy from a branch**, then select the `main` branch and `/ (root)` folder.

## Contact form

The contact button opens the public Pilea Studio Jira form. Its URL is configured on the element with `data-contact-link` in `index.html`.

Do not add an Atlassian API token to this repository. GitHub Pages is public and cannot safely hold server-side credentials.
