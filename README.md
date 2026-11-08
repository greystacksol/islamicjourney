# Islamic Journey

The life of the Prophet ﷺ and the Khilafah of the four Rightly Guided Caliphs on one timeline, with the Quran in revelation order, the people around him, the hadith and the full narrative stories.

Website: https://islamicjourney.org

## Files

- `index.html`: the whole site (HTML, CSS and JavaScript in one file)
- `stories.json`: the full story for each event
- `quran-data.json`: Quran text and translations (from QuranEnc)

It is a static site with no build step. Serve the folder from any web server. The JSON files load with `fetch`, so open it through a server, not by double-clicking `index.html`.

To preview locally:

```
python3 -m http.server 8000
```

Then open http://localhost:8000

## Status

The content is awaiting scholar review before public launch.

Search engines are blocked for now by `robots.txt`, a `noindex` meta tag in `index.html` and an `X-Robots-Tag` header in `.htaccess`. Remove all three at launch.
