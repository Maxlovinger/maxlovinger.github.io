# maxlovinger.github.io

My first personal website, built in summer 2024 with plain HTML and CSS after a set of online web development courses. It's hosted on GitHub Pages.

Live: [maxlovinger.github.io](https://maxlovinger.github.io)

> This is the original 2024 version. My current portfolio is at [maxlovinger.vercel.app](https://maxlovinger.vercel.app).

## Pages

| Page | File |
|---|---|
| Landing | `index.html` |
| About | `Home.html` |
| Resume | `Resume.html` |
| Projects | `Projects.html` |
| Contact | `Contact.html` |

Each page has its own stylesheet (`HomeDesign.css`, `ResumeDesign.css`, `ProjectDesign.css`, `ContactDesign.css`, ...).

## Projects shown

Small Python tools I wrote to automate tasks at an internship:

- **Auto Email Sender** - reads a CSV of email addresses and sends a message you write to each one (`EmailSender.html`)
- **Clipboard Copier** - custom hotkeys that copy saved prompts to the clipboard, for fast replies when recruiting on Indeed (`HotkeyMaker.html`)
- **Instagram Bot** - reads a list of usernames, looks up each account's ID, and sends each one a message (`InstaBot.html`)
- **This website** - the HTML and CSS behind the site (`WebPageCode.html`)

## Run it locally

No build step. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server
```

Optimized for desktop.
