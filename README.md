### Hi there, I'm [Hoang Phuc][website] 👋


## I'm a Sophomore at Hanoi University of Science and Techonology !!

- 🔭 I have finished 2 courses: [Machine Learning][course]! and [Deep Learning Specialization][course2]!
- 🌱 I'm studying computer science💯
- ⚡ Fun fact: I love basketball ️🏀

### Connect with me:

[<img align="left" alt="codeSTACKr | Facebook" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/facebook.svg" />][facebook]
[<img align="left" alt="codeSTACKr | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]
[<img align="left" alt="codeSTACKr | Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />][instagram]

<br />

### Languages and Tools:
<img align="left" alt="codeSTACKr | Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/python.svg">
<img align="left" alt="codeSTACKr | Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/cplusplus.svg">
<img align="left" alt="codeSTACKr | Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/c.svg">
<img align="left" alt="codeSTACKr | Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/visualstudio.svg">
<img align="left" alt="codeSTACKr | Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/pycharm.svg">
<img align="left" alt="codeSTACKr | Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/jupyter.svg">

<br />
<br />





[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=huyhoang18112k2&langs_count=8)](https://github.com/anuraghazra/github-readme-stats)


[website]: https://www.linkedin.com/in/huy-ho%C3%A0ng-l%C3%AA-a34b3021b/
[course]: https://www.coursera.org/account/accomplishments/certificate/T6MZQKY8GTKS
[facebook]: https://www.facebook.com/profile.php?id=100011026607041
[instagram]: https://www.instagram.com/troidaysao/
[linkedin]: https://www.linkedin.com/in/huy-ho%C3%A0ng-l%C3%AA-a34b3021b/



#### All inbuilt themes :-

dark, radical, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, highcontrast, dracula

<img src="https://res.cloudinary.com/anuraghazra/image/upload/v1595174536/grs-themes_l4ynja.png" alt="GitHub Readme Stats Themes" width="600px"/>

You can look at a preview for [all available themes](./themes/README.md) or checkout the [theme config file](./themes/index.js) & **you can also contribute new themes** if you like :D

### Customization

You can customize the appearance of your `Stats Card` or `Repo Card` however you wish with URL params.

#### Common Options:

- `title_color` - Card's title color _(hex color)_
- `text_color` - Body text color _(hex color)_
- `icon_color` - Icons color if available _(hex color)_
- `border_color` - Card's border color _(hex color)_. (Does not apply when `hide_border` is enabled)
- `bg_color` - Card's background color _(hex color)_ **or** a gradient in the form of _angle,start,end_
- `hide_border` - Hides the card's border _(boolean)_
- `theme` - name of the theme, choose from [all available themes](./themes/README.md)
- `cache_seconds` - set the cache header manually _(min: 1800, max: 86400)_
- `locale` - set the language in the card _(e.g. cn, de, es, etc.)_
- `border_radius` - Corner rounding on the card_

##### Gradient in bg_color

You can provide multiple comma-separated values in bg_color option to render a gradient, the format of the gradient is :-

```
&bg_color=DEG,COLOR1,COLOR2,COLOR3...COLOR10
```

> Note on cache: Repo cards have a default cache of 4 hours (14400 seconds) if the fork count & star count is less than 1k, otherwise, it's 2 hours (7200 seconds). Also, note that the cache is clamped to a minimum of 2 hours and a maximum of 24 hours.

#### Stats Card Exclusive Options:

- `hide` - Hides the specified items from stats _(Comma-separated values)_
- `hide_title` - _(boolean)_
- `hide_rank` - _(boolean)_ hides the rank and automatically resizes the card width
- `show_icons` - _(boolean)_
- `include_all_commits` - Count total commits instead of just the current year commits _(boolean)_
- `count_private` - Count private commits _(boolean)_
- `line_height` - Sets the line-height between text _(number)_
- `custom_title` - Sets a custom title for the card
- `disable_animations` - Disables all animations in the card _(boolean)_

#### Repo Card Exclusive Options:

- `show_owner` - Show the repo's owner name _(boolean)_

#### Language Card Exclusive Options:

- `hide` - Hide the languages specified from the card _(Comma-separated values)_
- `hide_title` - _(boolean)_
- `layout` - Switch between two available layouts `default` & `compact`
- `card_width` - Set the card's width manually _(number)_
- `langs_count` - Show more languages on the card, between 1-10, defaults to 5 _(number)_
- `exclude_repo` - Exclude specified repositories _(Comma-separated values)_
- `custom_title` - Sets a custom title for the card

> :warning: **Important:**
> Language names should be uri-escaped, as specified in [Percent Encoding](https://en.wikipedia.org/wiki/Percent-encoding)
> (i.e: `c++` should become `c%2B%2B`, `jupyter notebook` should become `jupyter%20notebook`, etc.) You can use
> [urlencoder.org](https://www.urlencoder.org/) to help you do this automatically.

#### Wakatime Card Exclusive Options:

- `hide` - Hide the languages specified from the card _(Comma-separated values)_
- `hide_title` - _(boolean)_
- `line_height` - Sets the line-height between text _(number)_
- `hide_progress` - Hides the progress bar and percentage _(boolean)_
- `custom_title` - Sets a custom title for the card
- `layout` - Switch between two available layouts `default` & `compact`
- `langs_count` - Limit number of languages on the card, defaults to all reported langauges
- `api_domain` - Set a custom API domain for the card, e.g. to use services like [Hakatime](https://github.com/mujx/hakatime) or [Wakapi](https://github.com/muety/wakapi)
- `range` – Request a range different from your WakaTime default, e.g. `last_7_days`. See [WakaTime API docs](https://wakatime.com/developers#stats) for list of available options.

---

# GitHub Extra Pins

GitHub extra pins allow you to pin more than 6 repositories in your profile using a GitHub readme profile.

Yay! You are no longer limited to 6 pinned repositories.

### Usage

Copy-paste this code into your readme and change the links.

Endpoint: `api/pin?username=anuraghazra&repo=github-readme-stats`

```md
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)
```

### Demo

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)

Use [show_owner](#customization) variable to include the repo's owner username

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats&show_owner=true)](https://github.com/anuraghazra/github-readme-stats)

# Top Languages Card

The top languages card show a GitHub user's most frequently used top language.

_NOTE: Top Languages does not indicate my skill level or anything like that, it's a GitHub metric of which languages have the most code on GitHub. It's a new feature of github-readme-stats._

### Usage

Copy-paste this code into your readme and change the links.

Endpoint: `api/top-langs?username=anuraghazra`

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
```

### Exclude individual repositories

You can use `?exclude_repo=repo1,repo2` parameter to exclude individual repositories.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&exclude_repo=github-readme-stats,anuraghazra.github.io)](https://github.com/anuraghazra/github-readme-stats)
```

### Hide individual languages

You can use `?hide=language1,language2` parameter to hide individual languages.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&hide=javascript,html)](https://github.com/anuraghazra/github-readme-stats)
```

### Show more languages

You can use the `&langs_count=` option to increase or decrease the number of languages shown on the card. Valid values are integers between 1 and 10 (inclusive), and the default is 5.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&langs_count=8)](https://github.com/anuraghazra/github-readme-stats)
```

### Compact Language Card Layout

You can use the `&layout=compact` option to change the card design.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)
```
