# Industry Python Contributions

Jekyll site for GitHub Pages to list contributions from students.

**Live site:** [https://oppkey.github.io/industry-python-contributions/](https://oppkey.github.io/industry-python-contributions/)

## Running the site locally

### Prerequisites

Install [rbenv](https://github.com/rbenv/rbenv) and [ruby-build](https://github.com/rbenv/ruby-build) to manage Ruby versions:

```bash
# macOS (Homebrew)
brew install rbenv ruby-build
```

Then add rbenv to your shell:

```bash
rbenv init
# Follow the instructions to add eval "$(rbenv init -)" to your shell config
```

### Install Ruby

```bash
rbenv install 3.3.0   # or a recent 3.x version
rbenv local 3.3.0
```

### Install dependencies and run Jekyll

```bash
bundle install
bundle exec jekyll serve
```

The site will be available at [http://localhost:4000/industry-python-contributions/](http://localhost:4000/industry-python-contributions/).
