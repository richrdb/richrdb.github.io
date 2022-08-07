## Willkommen bei gigachad.eu

Du kannst den [Editor auf GitHub](https://github.com/richrdb/richrdb.github.io/edit/main/index.md) verwenden, um die Inhalte deiner Website in Markdown-Dateien zu pflegen und in der Vorschau anzuzeigen.

Immer, wenn du in dieses Repository einreichst, wird GitHub Pages [Jekyll](https://jekyllrb.com/) ausführen, um die Seiten deiner Website aus den Inhalten in deinen Markdown-Dateien neu zu erstellen.

### yt-dlp CLI

yt-dlp CLI ist eine leichte und einfach zu bedienende Kommandozeilenschnittstelle zum Herunterladen von Audio und Video.

```markdown
Write-Output "yt-dlp CLI"
$url = Read-Host -Prompt "Video-URL"
.\yt-dlp.exe -x --audio-format mp3 -o "%(channel)s\%(release_year)s - %(album)s\%(playlist_autonumber)s - %(title)s - %(artist)s.%(ext)s" $url
Write-Output "Process finished!"
Pause
```

Weitere Einzelheiten findest du unter [Grundlegende Schreib- und Formatierungssyntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll-Themen

Deine Pages-Seite verwendet das Layout und die Stile des Jekyll-Themas, das du in deinen [Repository-Einstellungen](https://github.com/richrdb/richrdb.github.io/settings/pages) ausgewählt hast. Der Name dieses Themas wird in der Jekyll-Konfigurationsdatei `_config.yml` gespeichert.

### Support oder Kontakt

Hast du Probleme mit Pages? Schau in unserer [Dokumentation](https://docs.github.com/categories/github-pages-basics/) nach oder wende dich an den [Support](https://support.github.com/contact) und wir helfen dir bei der Lösung des Problems.
