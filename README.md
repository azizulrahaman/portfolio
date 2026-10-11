# Azizul Rahaman

Portfolio site: SOC analyst, CompTIA Security+ (SY0-701), M.S. in Cybersecurity and Network Administration from Touro University (2026).

**Live:** https://azizulrahaman.github.io/portfolio/

## Run it locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Edit links

Contact links, the resume button, and the contact form key live in the `window.SITE` block at the top of `index.html`. Leave a value empty (`""`) to hide that link. To add a resume, put `resume.pdf` next to `index.html` and set `resume: "resume.pdf"`.

## Contact form

The form sends through [Web3Forms](https://web3forms.com), which emails each message to the address the access key was created with. The key in `formKey` is public by design. Replies go straight to the sender's email address.

Design inspired by Khaliduzzaman Mredul's portfolio.
