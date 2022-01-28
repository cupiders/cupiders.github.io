# [Source for cupider.github.io powered by Jekyll theme]

[![LICENSE](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/mmistakes/minimal-mistakes/master/LICENSE)
[![Jekyll](https://img.shields.io/badge/jekyll-%3E%3D%203.7-blue.svg)](https://jekyllrb.com/)
[![Ruby gem](https://img.shields.io/gem/v/minimal-mistakes-jekyll.svg)](https://rubygems.org/gems/minimal-mistakes-jekyll)


**cupider.github.io** is powered by Jekyll theme "Minimal Mistakes" which is a flexible two-column Jekyll theme, perfect for building personal sites, blogs, and portfolios. As the name implies, styling is purposely minimalistic to be enhanced and customized :smile:.

:sparkles: Read more about [Minimal Mistakes Jekyll theme](https://mmistakes.github.io/minimal-mistakes/).

## Note

- cupiders.github.io is initiated from January 28th 2022.
- Only accessible to cupid developers in KAERI.
- Git-hub domain is owned by So-Hyun Park (bibirom10@kaeri.re.kr).
- Nine different skins (color variations) are available.
- Comment engines are supportive ([Disqus](https://disqus.com/), [Discourse](https://www.discourse.org/), static-based via [Staticman](https://staticman.net/), and [giscus](https://giscus.app/)) but not implemented.
- Search engines are available but not implemented.
- [Google Analytics](https://www.google.com/analytics/) support.
- UI localized text in English (default), Arabic (عربي), Chinese, French (Français), German (Deutsch), Japanese, Korean.

---

## Installation

There are two ways to install: as a [gem-based theme](https://jekyllrb.com/docs/themes/#understanding-gem-based-themes), as a [remote theme](https://blog.github.com/2017-11-29-use-any-theme-with-github-pages/) (**GitHub Pages compatible**).

### Gem-based method

In order for local serve test, Gem-based method is recommended in advance. Yet all of the necessary directories will be read and processed during Jekyll’s build process.

1. install [Ruby for Windows](https://rubyinstaller.org/downloads/) in order to utilize `jekyll`

2. install `bundler` by running the following command: 

   ```bash
   gem install bundler
   ```

3. Go to your local repository (download path of source code) and Add the following to your `Gemfile`:

   ```ruby
   gem "minimal-mistakes-jekyll"
   gem "tzinfo-data"
   gem "wdm", "~> 0.1.0"
   ```

4. Fetch and update bundled gems by running the following command:

   ```bash
   bundle install
   ```

5. **Set the `theme` in your project's Jekyll `_config.yml` file:**

   ```yaml
   theme: minimal-mistakes-jekyll
   ```

6. Test the theme by running the following command: 

   ```bash
   bundle exec jekyll serve
   ```
   open your browser at `http://localhost:4000/`.


### Remote theme method

After edit the source codes, publishing the theme through **Gitpage** requires some modifications.


1. Replace the contents of your `Gemfile` with the following:

   ```ruby
   source "https://rubygems.org"

   gem "minimal-mistakes-jekyll"
   gem "tzinfo-data"   
   gem "wdm", "~> 0.1.0"

   group :jekyll_plugins do
      gem "jekyll-paginate"
      gem "jekyll-sitemap"
      gem "jekyll-gist"
      gem "jekyll-feed"
      gem "jekyll-include-cache"
   end
   ```

2. Fetch and update bundled gems by running the following command:

   ```bash
   bundle install
   ```

3. **Add `remote_theme:    "mmistakes/minimal-mistakes"` to your `_config.yml` file. Remove `theme:` entry.**

4. Push source codes into github repository.

As modifications are made to the theme and test site, it will regenerate and you should see the changes in the browser after a refresh.


## Usage

For detailed instructions on how to configure, customize, add/migrate content, and more read the [theme's documentation](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/).


## Skins (color variations)

This theme comes in nine different skins (in addition to the default one).

| `air` | `contrast` | `dark` |
| --- | --- | --- |
| [![air skin](https://mmistakes.github.io/minimal-mistakes/assets/images/air-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/air-skin-archive-large.png) | [![contrast skin](https://mmistakes.github.io/minimal-mistakes/assets/images/contrast-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/contrast-skin-archive-large.png) | [![dark skin](https://mmistakes.github.io/minimal-mistakes/assets/images/dark-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/dark-skin-archive-large.png) |

| `dirt` | `mint` | `sunrise` |
| --- | --- | --- |
| [![dirt skin](https://mmistakes.github.io/minimal-mistakes/assets/images/dirt-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/dirt-skin-archive-large.png) | [![mint skin](https://mmistakes.github.io/minimal-mistakes/assets/images/mint-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/mint-skin-archive-large.png) | [![sunrise skin](https://mmistakes.github.io/minimal-mistakes/assets/images/sunrise-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/sunrise-skin-archive-large.png) |

| `aqua` | `neon` | `plum` |
| --- | --- | --- |
| [![aqua skin](https://mmistakes.github.io/minimal-mistakes/assets/images/aqua-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/aqua-skin-archive-large.png) | [![neon skin](https://mmistakes.github.io/minimal-mistakes/assets/images/neon-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/neon-skin-archive-large.png) | [![plum skin](https://mmistakes.github.io/minimal-mistakes/assets/images/plum-skin-archive.png)](https://mmistakes.github.io/minimal-mistakes/assets/images/plum-skin-archive-large.png) |

---