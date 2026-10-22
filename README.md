# The Rice Notes — a static GitHub Pages site

A responsive one-page personal football website about Declan Rice, built entirely with HTML and CSS. No accounts, databases, JavaScript, or paid hosting are needed.

## Files

- `index.html` — the complete webpage and content
- `style.css` — layout, typography and responsive styling
- `assets/declan-rice.png` — the photo supplied by the student

**Keep all three at exactly these relative paths** when uploading to GitHub; do not upload only `index.html`.

## Preview locally

Open `index.html` in your browser. Check the image, layout and navigation links.

## Publish with GitHub Pages

1. Sign into GitHub. You do **not** need to change your existing username.
2. Create a **public** repository named `YOUR-EXISTING-USERNAME.github.io` (replace the placeholder with your exact GitHub username).
3. Upload `index.html`, `style.css`, and the **assets folder with its image** to the repository root. Commit the changes.
4. Open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, then save (if it isn't already configured).
5. Visit `https://YOUR-EXISTING-USERNAME.github.io/` when deployment is ready. Check the page on both desktop and mobile.
6. Capture screenshots of the GitHub repository, Pages deployment settings, and the live webpage for Question 2's report.

If your actual GitHub username has a different spelling from your student name, the repository and URL use your **GitHub username**, not necessarily your real name.

## Q2 network analysis checklist

After the website is live, use your **own actual URL** to run and screenshot:

- Domain/IP: `nslookup YOUR-EXISTING-USERNAME.github.io`
- Latency: `ping YOUR-EXISTING-USERNAME.github.io` (on macOS, press Ctrl+C after several replies)
- Network route (macOS/Linux): `traceroute YOUR-EXISTING-USERNAME.github.io`
- Network route (Windows): `tracert YOUR-EXISTING-USERNAME.github.io`
- Wireshark: start capture, visit the webpage in a browser, stop capture. Explore `dns`, `tcp`, `tls`, and/or `quic` packets actually observed. DNS may be cached and some browsers use HTTP/3/QUIC rather than TCP/TLS.

Write a short explanation for **every** screenshot: what was tested, what result appeared, and what it means. Do not invent results or pretend an empty capture proves a specific protocol. A host may ignore `ping` or `traceroute` probes even when its website works.

## Content and photo notes

- This is a **personal fan site**, not an official Arsenal / Premier League website.
- If the supplied image was taken from the internet, **confirm permission or suitable usage rights before publishing publicly**. Adding a credit alone does not replace permission when permission is required. Replace `assets/declan-rice.png` with a properly licensed image if needed.
- You may edit any text in `index.html` to better reflect your own feelings.
