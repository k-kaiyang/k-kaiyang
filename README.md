# Koh Kai Yang: portfolio site

Plain HTML and CSS, with no build step.

## Pages
- `index.html`: home page with hero, 3 case-study cards, About and Contact
- `umapyoi-state-machine.html`: flagship case study
- `astar-pathfinding.html`: constrained case study
- `flow-field.html`: specific-skill case study
- `KohKaiYang_Resume.docx`: the Seatrium resume, linked from "Download resume"

## Before publishing
1. **Fill the yellow boxes.** Each case study has "What I tested" and "What failed" boxes marked "Add: ...". Replace the text with your own and remove `class="todo"`.
2. **Add images and videos.** Put files in an `assets/` folder, then replace each dashed grey box:
   - Image: `<figure class="media"><img src="assets/dungeon.png" alt="Generated dungeon with flow arrows"></figure>`
   - Video: `<figure class="media"><video src="assets/umapyoi.mp4" controls muted></video></figure>`
   - YouTube: paste YouTube's embed `<iframe>` inside `<figure class="media">`.
   - Keep each video under about 25 MB so it loads quickly. For anything longer, use YouTube.

## Publish on GitHub Pages (free)
1. On your GitHub account, create a public repo named `<your-username>.github.io`.
2. Upload every file in this folder (drag and drop on github.com works).
3. Go to **Settings → Pages**, set the source to the `main` branch, and save.
4. The site goes live at `https://<your-username>.github.io` within a few minutes. Open it in a private browser window to check that it loads without a login.

## Staying on Wix instead
Wix can't import these files. Recreate each page in the Wix editor and paste in the text from the HTML files. Use one Wix page per case study, with the same six headings.
