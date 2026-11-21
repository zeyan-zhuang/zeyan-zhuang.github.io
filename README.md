# zeyan-zhuang.github.io

Run these commands from the project directory with Python 3.

Page sources:

- `index.jemdoc`: profile, About me, and News.
- `biography.jemdoc`: academic appointments, education, and service.
- `publications.jemdoc`: complete publications and preprints.

Navigation is configured in `MENU`. Rebuild all pages after changing the menu.

Build the homepage:

```sh
python3 ./jemdoc -c mysite.conf index.jemdoc
```

Build all pages:

```sh
python3 ./jemdoc -c mysite.conf *.jemdoc
```

The generated HTML files are saved beside their `.jemdoc` sources. Open
`index.html` in a browser to preview the homepage and refresh after rebuilding.
If `python` already points to Python 3, it can be used instead of `python3`.
