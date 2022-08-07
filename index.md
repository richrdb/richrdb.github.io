## Welcome to gigachad.eu

You can use the [editor on GitHub](https://github.com/richrdb/richrdb.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### yt-dlp CLI

yt-dlp CLI is a lightweight and easy-to-use command line interface for downloading audio and video. Here is an example:

```markdown
Write-Output "yt-dlp CLI"
$url = Read-Host -Prompt "Video-URL"
.\yt-dlp.exe -x --audio-format mp3 -o "%(channel)s\%(release_year)s - %(album)s\%(playlist_autonumber)s - %(title)s - %(artist)s.%(ext)s" $url
Write-Output "Process finished!"
Pause
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/richrdb/richrdb.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
