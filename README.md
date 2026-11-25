# The Last Default Slide

A live walk through the last four weeks of AI, math, and science.

Open the [live experience](https://fibonacciai.github.io/last-default-slide/).

This is a static page. Nothing is sent anywhere. Sound starts after you tap.

## Update later

From the box copy of the deck:

```bash
cd /workspace/lbs
python3 src/build.py
cp last-default-slide.html site/index.html
# if share assets changed: cp share/og.jpg share/favicon-32.png share/apple-touch-icon.png site/
cd site
git add -A
git commit -m "Update The Last Default Slide"
git push
```

GitHub Pages publishes from the `main` branch, root folder. The public URL updates in about a minute.
