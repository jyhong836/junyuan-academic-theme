## Junyuan's Customized Academic Website

[![Hugo Theme](https://img.shields.io/badge/Hugo-black.svg?style=flat&logo=Hugo&color=orange&label=Theme)](https://github.com/jyhong836/junyuan-academic-theme) [![Demo](https://img.shields.io/badge/Hugo-black.svg?style=flat&logo=Hugo&color=orange&label=Demo)](https://jyhong.gitlab.io/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 

This the theme customized and used by [Junyuan Hong](https://jyhong.gitlab.io) (click to check the demo).
The theme is based on [Wowchemy Academic Theme](https://github.com/wowchemy/starter-hugo-academic) driven by [Hugo](https://gohugo.io/). The customization was first created by [matteocourthoud](https://matteocourthoud.github.io/).

Guidance for deployment and customizations:
* [matteocourthoud's guide](https://matteocourthoud.github.io/post/website/).
* The full set of [codes](https://github.com/jyhong836/jyhong.gitlab.io) for reproducing [Junyuan's website](https://jyhong.gitlab.io).

Features added by the theme:
* In publication section, you can set filter buttons, like selected and specific tags, which can automatically adjust the displayed papers.
* `Showcase` design view (`design.view` in `content/home/featured`) for the featured widget. The `showcase` view is derived from portfolio's `showcase` view and is adjusted with a larger figure and text.
* Avatar will be stick on the top when scrolling.
* New citation format with venue and year badge at the beginning. Authors in the second line. Link buttons will not in new line to save space.

Feel free to use :smile:.

## How to use

You can directly start from [my website codes](https://github.com/jyhong836/jyhong.gitlab.io) or follow the below instruction to use the theme only.
1. Run `git clone git@github.com:jyhong836/junyuan-academic-theme.git` in your `themes` folder.
2. Update the imported `module` in `config/_default/config.yaml`.
    ```yaml
    module:
        imports:
            - path: github.com/wowchemy/wowchemy-hugo-modules/wowchemy-cms
            # - path: github.com/wowchemy/wowchemy-hugo-modules/wowchemy
            - path: junyuan-academic-theme
    ```
3. Refer to [my codes](https://github.com/jyhong836/jyhong.gitlab.io) to use the theme.

Useful customization info:
* Color customization by editing `data/themes/<theme-name>.toml`.
