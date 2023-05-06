## Junyuan's Customized Academic Website

This the theme customized and used by [Junyuan Hong](https://jyhong.gitlab.io) (click to check the demo).
The theme is based on [Wowchemy Academic Theme](https://github.com/wowchemy/starter-hugo-academic) driven by [Hugo](https://gohugo.io/). The customization was first created by [matteocourthoud](https://matteocourthoud.github.io/).

Guidance for deployment and customizations:
* [matteocourthoud's guide](https://matteocourthoud.github.io/post/website/).
* The full set of codes for reproducing [Junyuan's website](https://github.com/jyhong836/jyhong.gitlab.io).

Feel free to use :smile:.

You can directly start from [my website codes](https://github.com/jyhong836/jyhong.gitlab.io) or follow the below instruction to use the theme only.
1. Run `git clone git@github.com:jyhong836/junyuan-academic-theme.git` in your `theme` folder.
2. Update the imported `module` in `config/_default/config.yaml`.
    ```yaml
    module:
    imports:
        - path: github.com/wowchemy/wowchemy-hugo-modules/wowchemy-cms
        # - path: github.com/wowchemy/wowchemy-hugo-modules/wowchemy
        - path: junyuan-academic-theme
    ```

Features added by the theme:
* In publication section, you can set filter buttons, like selected and specific tags, which can automatically adjust the displayed papers.
* `Showcase` design view (`design.view` in `content/home/featured`) for the featured widget. The `showcase` view is derived from portfolio's `showcase` view and is adjusted with a larger figure and text.
* Avatar will be stick on the top when scrolling.
* New citation format with venue and year badge at the beginning. Authors in the second line. Link buttons will not in new line to save space.

Useful info:
* Color customization by editing `data/themes/<theme-name>.toml`.
