# Docs: posts and write-ups

| File | What it is | Where to use it |
|---|---|---|
| [pitch.md](pitch.md) | Project story, short pitch, how it scores on design / usability / creativity / content, 30-second video script | Contest entries, intro posts, video |
| [pcbway/](pcbway/) | One ready-to-paste write-up per board (title, summary, tags, description, specs, order settings) | One shared project per board |
| [wordpress-post.html](wordpress-post.html) | Full blog post in WordPress block format, with SEO title, slug, meta description and tags at the top | Your website |

## Posting each board as a shared project

1. Open `pcbway/NN-Board-Name.md`.
2. Copy **Title** and **Short description** into the matching boxes, and add the **Tags**.
3. Paste everything under **Description** into the project description.
4. Upload the Gerber zip named at the bottom of the file, from `../gerber/`.
5. Add pictures. Real photos of the board, front and back plus a finished build, score much better than renders.

## Posting the blog article on WordPress

1. Create a new post and set the title, slug, category and tags from the comment at the top of `wordpress-post.html`.
2. Open the three-dot menu (top right), choose **Code editor**, and paste the whole file.
3. Choose **Exit code editor**. The headings, tables, images and buttons all appear as normal blocks.
4. Set a featured image, and swap the layout images for photos once you have real boards.
