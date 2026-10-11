[README.md](https://github.com/user-attachments/files/33305949/README.md)
# Lead Time

Project dates, reminders and plan review for standby generator installations.

The whole app is one file, `index.html`. There is nothing to build or install.

## Put it online with GitHub Pages

1. Create a new repository on GitHub (for example `lead-time`). On a free account it must be **Public**.
2. Click **Add file → Upload files**, drag in `index.html` and this `README.md`, then click **Commit changes**.
3. Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, pick the **main** branch and the **/ (root)** folder, and click **Save**.
4. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/lead-time/`.

To update the site later, upload a new `index.html` over the old one.

## Where your data lives

- Projects are saved in the browser you use (its local storage), on that computer only. Nothing is sent to GitHub.
- Anyone who opens the site gets their own empty copy. They can't see your projects.
- Clearing your browser's site data erases your projects, so use **Settings → Download backup** regularly.
- To bring projects over from the Claude version or another computer: **Download backup** there, then **Restore from backup** here.

## Plan and submittal review

On this website, plan review uses your own Anthropic API key:

1. Create a key at https://console.anthropic.com (reviews are billed to that account).
2. In the site, open **Settings → Plan review**, paste the key and click **Save key**.

The key is stored only in that browser. **Never put your API key in `index.html` or any file in the repository**: the repository is public, and anyone could copy it.

## What works differently from the Claude version

- Reminder emails open in your mail app with the **Email me** buttons, same as before. The page can't send email while it's closed; use **Download calendar file** for pop-up alerts in Outlook, Google or Apple Calendar.
- Uploaded plan files aren't kept after the review (the results are).
