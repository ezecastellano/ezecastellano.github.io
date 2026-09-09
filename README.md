# ezecastellano.github.io

Personal academic site — publications, research, and background.
Live at https://ezecastellano.github.io/

## Running locally

This site is built with [Jekyll](https://jekyllrb.com/) via [GitHub Pages](https://pages.github.com/). To preview changes locally before pushing:

### 1. Install Ruby (via rbenv)

Don't use macOS's built-in system Ruby — install a proper version manager instead:

```bash
brew install rbenv ruby-build
rbenv install 3.2.2
rbenv local 3.2.2
```

Make sure your shell picks up rbenv (add to `~/.zshrc` if not already present):

```bash
eval "$(rbenv init -)"
```

Then restart your terminal (or `source ~/.zshrc`) and verify:

```bash
which ruby   # should point to ~/.rbenv/..., not /usr/bin/ruby
```

### 2. Install dependencies

```bash
gem install bundler
bundle install
```

If `bundle install` fails on `nokogiri` (common on Apple Silicon):

```bash
brew install libxml2 libxslt
bundle config set build.nokogiri --use-system-libraries
bundle install
```

### 3. Serve the site locally

```bash
bundle exec jekyll serve
```

Open [http://127.0.0.1:4000](http://127.0.0.1:4000) to preview. The server watches for file changes and rebuilds automatically.

## Notes

- `Gemfile` / `Gemfile.lock` pin the same Jekyll + plugin versions GitHub Pages uses in production, so the local build matches what's actually deployed.
- `.ruby-version` pins the Ruby version for this repo via rbenv.
- Build output (`_site/`) and local bundler config (`.bundle/`) are gitignored — they're regenerated automatically and shouldn't be committed.
