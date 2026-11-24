# Suyeon Shin: portfolio site

Everything is in one file: `index.html`. Your content (every sheet, row, thread and photo) lives in a JSON block near the bottom of that file.

## Put it on Vercel
1. Create a GitHub repository and upload `index.html` (and this README).
2. On vercel.com, choose **Add New → Project**, import the repository and press **Deploy**. No build settings are needed.

## Edit the site
1. Open your live site with `?edit` at the end, e.g. `https://your-site.vercel.app/?edit`. Visitors never see the edit buttons.
2. On any sheet except Personal, click a row to edit it in the side panel: text, link, thread colours, ★ highlight, photos, move up/down, duplicate or delete.
3. On Personal, click any cell to edit the whole page in one form: your name and tagline, photo, details row, About, the list column, links, the green button and the footer. Your five bios are saved there too (they're not shown on the site).
4. **+ Row** and **+ Section** add a row below the row you last opened.
5. **Sheet settings** renames the sheet, renames or resizes its columns, moves it left or right, or deletes it. The **+** at the bottom left adds a new sheet.
6. **Edit threads** changes each thread's name, colour, question and write-up.
7. Your changes save as a draft on that device as you type. When you're happy, press **Download site**, then replace `index.html` in GitHub with the downloaded file (Add file → Upload files). Vercel redeploys automatically in about a minute.

## Photos
- **Upload photos** in a row's panel resizes each image and stores it inside `index.html`. This is the easiest option, but every photo makes the file bigger.
- For lots of photos, add a `photos` folder to the repository, upload the images there, and use **Add by URL** with a path like `/photos/vivocity.jpg`.

## Backups
**Export JSON** saves just your content; **Import JSON** loads it back.
