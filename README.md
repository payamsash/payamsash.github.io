# payamsash.github.io

Personal website of Payam S. Shabestari: https://payamsash.github.io

Built with Jekyll on the [AcademicPages](https://github.com/academicpages/academicpages.github.io) theme
(a fork of [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/), MIT licensed, see `LICENSE`).
GitHub Pages builds and publishes the site automatically on every push to `master`.

## Where things live

| What | File |
|---|---|
| Name, bio, sidebar links | `_config.yml` (`author:` section) |
| Top menu | `_data/navigation.yml` |
| Home page | `_pages/about.md` |
| CV / Publications / Software / Talks | `_pages/cv.md`, `papers.md`, `software.md`, `talks.md` |
| Look & feel (colours, fonts, dark mode) | `_sass/_custom.scss` |
| Images, video, logos | `images/` |
| CV PDF | `files/Payam_Shabestari_CV.pdf` |

## Preview locally

One-time setup (macOS, Homebrew):

```sh
brew install ruby
export PATH="/opt/homebrew/opt/ruby/bin:$PATH"   # add this line to ~/.zshrc
bundle config set --local path vendor/bundle
bundle install
```

Then, every time:

```sh
bundle exec jekyll serve --livereload --config _config.yml,_config.dev.yml
```

and open http://localhost:4000. Edits to pages and styles reload automatically;
restart the command after changing `_config.yml`.

## Regenerate the CV PDF

With the local preview running:

```sh
"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" --headless=new \
  --no-pdf-header-footer --print-to-pdf=files/Payam_Shabestari_CV.pdf http://localhost:4000/cv/
```
