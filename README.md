# Useful-Alfred-Workflows
## Combined list of the Alfred workflows that I regularly use

### Change Case: 1.5.1
| [Source](https://github.com/gillibrand/alfred-change-case) 
| 🍺️ [Jay Gillibrand](https://github.com/gillibrand)

Changes the case of text selected, provided, or on the clipboard to UPPERCASE, lowercase, Title Case, CamelCase, kebab-case, or snake_case.
![Screenshot](https://github.com/gillibrand/alfred-change-case/blob/master/changecase.jpg)

---

### Emoji Taco: 2.0.2 🌮
| [Repo](https://github.com/jeeftor/EmojiTaco) 
| 🍺️ [Jeeftor](https://github.com/jeeftor)

Scrapes Unicode.org to pull down the latest set of EMOJI!!. 
Use the **e** command to search for emoji.

![tac](https://github.com/jeeftor/EmojiTaco/blob/master/docs/taco.png)

You can also use the `-` to exclude items from a search such as:

![](https://github.com/jeeftor/EmojiTaco/blob/master/docs/complexsearch.png)

---

### LinkClean: 
| [Repo](https://github.com/vitorgalvao/alfred-workflows/tree/master/LinkClean) 
| 🍺️ [Vítor Galvão](https://github.com/vitorgalvao)

Clean clutter from URLs such as all sorts of [`utm_` variants](http://www.bytefive.com/blogs/understanding-utm_source-utm_medium-and-utm_campaign) and subdomains like `m.` for mobile sites.

Run `lc` and input a URL, or leave it blank to use your clipboard contents. Action it and a clean link will be copied to your clipboard and pasted to your frontmost app. If given a shotened URL, redirects will be followed before cleaning.

![](https://i.imgur.com/BOlDUmt.png)

---

### Movie and TV Show Search: 
| [Repo](https://github.com/tmcknight/Movie-and-TV-Show-Search-Alfred-Workflow) 
| 🍺️ [tmcknight](https://github.com/tmcknight)

Search for a movie or tv show and get a few ratings from IMDb, Rotten Tomatoes, Metacritic.
Even throws direct links to Letterboxd, JustWatch, and a Trailer on YouTube if available.

![Sample](https://raw.githubusercontent.com/tmcknight/Movies-Alfred-Workflow/master/example.gif)

---

### OneUpdater: 
| [Repo](https://github.com/vitorgalvao/alfred-workflows/tree/master/OneUpdater) 
| 🍺️ [Vítor Galvão](https://github.com/vitorgalvao)

As the name suggests, this is OneUpdate to rule them all. An auto-update patch you can put into (almost) all of your Alfred workflows. With minimal set-up, it allows you to let each workflow update itself from source to the latest version automagically. Clear instruction on setup at the repo linked above.

![Setting up OneUpdater with Run Script](https://i.imgur.com/87AqLvI.gif)

The top lines must be set, and the rest of the code should be left untouched.

* `remote_info_plist` is the URL to the workflow’s up-to-date `info.plist` on a server.
* `workflow_url` and `download_type` work in tandem. `download_type` must be one of `direct`, `page`, or `github_release`.
  * When `direct`, `workflow_url` must be a direct link to a Workflow file.
  * When `page`, `workflow_url` must be a link to a download page.
  * When `github_release`, `workflow_url` must be of the form `username/repo`.
* `frequency_check` is the number of day between update checks. Set it to `0` when testing, so it fires on every use.

Example:

```
readonly remote_info_plist='https://raw.githubusercontent.com/vitorgalvao/alfred-workflows/master/ShortFilms/source/info.plist' 
readonly workflow_url='https://raw.githubusercontent.com/vitorgalvao/alfred-workflows/master/ShortFilms/ShortFilms.alfredworkflow'
readonly download_type='direct'
readonly frequency_check='4'
```
---

### RightClick: 
| [Repo](https://github.com/vitorgalvao/alfred-workflows/tree/master/RightClick) 
| 🍺️ [Vítor Galvão](https://github.com/vitorgalvao)

Press a shortcut to simulate a right click in the Finder and use the context without leaving the keyboard.

---

### YouTube Video Download: 
| [Repo](https://github.com/nickytonline/alfred-workflows/tree/master/workflows) 
| 🍺️ [Nick Taylor](https://github.com/nickytonline)


 
