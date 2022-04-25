# Useful-Alfred-Workflows


## Combined list of the Alfred workflows that I regularly use   



### Change Case: v1.5.1
| [Download Workflow](https://github.com/jun6lee/Useful-Alfred-Workflows/blob/main/Change.Case.alfredworkflow)
| [Source Repo](https://github.com/gillibrand/alfred-change-case) 
| 🍺️ [Jay Gillibrand](https://github.com/gillibrand)

Changes the case of text selected, provided, or on the clipboard to UPPERCASE, lowercase, Title Case, CamelCase, kebab-case, or snake_case.

![Screenshot](https://github.com/gillibrand/alfred-change-case/blob/master/changecase.jpg)

---

### CleanApp: v1.0
| [Download Workflow](https://github.com/jun6lee/Useful-Alfred-Workflows/blob/main/CleanApp.alfredworkflow)
| 🍺️ Myself

Sends application to the freeware AppCleaner for tidy removal. The app can be installed as a cask via `brew install --cask appcleaner`

---

### Emoji Taco: v2.0.1 🌮
| [Download Workflow](https://github.com/jun6lee/Useful-Alfred-Workflows/blob/main/Emoji_Taco-2.0.1.alfredworkflow)
| [Source Repo](https://github.com/jeeftor/EmojiTaco) 
| 🍺️ [Jeeftor](https://github.com/jeeftor)

One-Time-Setup: Type `init emoji` | Wait for completion as itscrapes Unicode.org to pull down the latest set of EMOJI!!. 

Use the **e** command to search for emoji.

![tac](https://github.com/jeeftor/EmojiTaco/blob/master/docs/taco.png)

You can also use the `-` to exclude items from a search such as:

![](https://github.com/jeeftor/EmojiTaco/blob/master/docs/complexsearch.png)

---

### Github v1.7.1
| [Download Workflow](https://github.com/jun6lee/Useful-Alfred-Workflows/blob/main/github.alfredworkflow)
| [Source Repo](https://github.com/gharlan/alfred-github-workflow) 
| 🍺️ [Gregor Harlan](https://github.com/gharlan)

One-Time-Setup: Type (`gh > login`) to authenticate your account. 

Search through GitHub (`gh`) and your GitHub Enterprise instance (`ghe`).

![](https://github.com/gharlan/alfred-github-workflow/blob/master/screenshot.png)

Prerequisites: Requires PHP, which is no longer pre-installed since macOS Montery.  
You can install it via [Homebrew](https://brew.sh) (`brew install php`).

--- 

### Google-Drive: v2022.10   
| [Download Workflow](https://github.com/alfredapp/google-drive-workflow/releases/latest/download/Google.Drive.alfredworkflow)
| [Source Repo](https://github.com/alfredapp/google-drive-workflow) 
| 🍺️ [Alfred](https://github.com/alfredapp)

Navigate your Google Drive.

---

### Kill Process v1.2.1
| [Download Workflow](https://github.com/jun6lee/Useful-Alfred-Workflows/blob/main/Kill%20Process.alfredworkflow)
| [Source Repo](https://github.com/ngreenstein/alfred-process-killer) 
| 🍺️ [Nathan Greenstein](https://github.com/ngreenstein)

Easily find and kill misbehaving processes. 

![screenshot: `kill it`](https://github.com/ngreenstein/alfred-process-killer/blob/master/screenshot1.png)

---

### LinkClean: v22.2
| [Download Workflow](https://github.com/jun6lee/Useful-Alfred-Workflows/blob/main/LinkClean.alfredworkflow)
| [Source Repo](https://github.com/vitorgalvao/alfred-workflows/tree/master/LinkClean) 
| 🍺️ [Vítor Galvão](https://github.com/vitorgalvao)

Clean clutter from URLs such as all sorts of [`utm_` variants](http://www.bytefive.com/blogs/understanding-utm_source-utm_medium-and-utm_campaign) and subdomains like `m.` for mobile sites.

Run `lc` and input a URL, or leave it blank to use your clipboard contents. Action it and a clean link will be copied to your clipboard and pasted to your frontmost app. If given a shotened URL, redirects will be followed before cleaning.

![](https://i.imgur.com/BOlDUmt.png)

---

### Movie and TV Show Search: v2.12.1
| [Download Workflow](https://github.com/jun6lee/Useful-Alfred-Workflows/blob/main/Movie.and.TV.Show.Search.alfredworkflow)
| [Source Repo](https://github.com/tmcknight/Movie-and-TV-Show-Search-Alfred-Workflow) 
| 🍺️ [tmcknight](https://github.com/tmcknight)

Search for a movie or tv show and get a few ratings from IMDb, Rotten Tomatoes, Metacritic.
Even throws direct links to Letterboxd, JustWatch, and a Trailer on YouTube if available.

![Sample](https://raw.githubusercontent.com/tmcknight/Movies-Alfred-Workflow/master/example.gif)


---

### OneUpdater: v22.1
| [Download Workflow](https://github.com/jun6lee/Useful-Alfred-Workflows/blob/main/OneUpdater.alfredworkflow)
| [Source Repo](https://github.com/vitorgalvao/alfred-workflows/tree/master/OneUpdater) 
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

### Open in Preview: v1.0
| [Download Workflow](https://github.com/jun6lee/Useful-Alfred-Workflows/blob/main/Open%20in...%20Preview.alfredworkflow)
| 🍺️ Myself

Through a customisable shortcut key, sends selected file item in Finder to open in Preview (rather than the default application set by the OS).

---

### Reminders: v75  
| [Download Workflow](https://github.com/surrealroad/alfred-reminders/blob/master/Reminders.alfredworkflow)
| [Source Repo](https://github.com/surrealroad/alfred-reminders) 
| 🍺️ [surrealroad](https://github.com/surrealroad/)

Create new reminders which get added to your default reminder list in Apple Reminders. To use, just type `r <some text>` into Alfred. `r help` for options. Many other options for alternate lists, current tab, etc.

---

### RightClick: v21.1
| [Download Workflow](https://github.com/jun6lee/Useful-Alfred-Workflows/blob/main/RightClick.alfredworkflow)
| [Source Repo](https://github.com/vitorgalvao/alfred-workflows/tree/master/RightClick) 
| 🍺️ [Vítor Galvão](https://github.com/vitorgalvao)

Press a shortcut to simulate a right click in the Finder and use the context without leaving the keyboard.

---

### Word-Search: v2.0.0
| [Download Workflow](https://github.com/jun6lee/Useful-Alfred-Workflows/blob/main/Word.Search.alfredworkflow)
| [Source Repo](https://github.com/jun6lee/Alfred-WordSearch) 
| 🍺️ [Isaac Pohl-Zaretsky](https://github.com/isaacpz) | Ported for Python3 Compatability by Myself

Look up synonyms with `syn`, antonyms with `ant`, rhyming words with `rhyme`.

---

### YouTube Video Download: v1
| [Download Workflow](https://github.com/jun6lee/Useful-Alfred-Workflows/blob/main/youtube-video-download.alfredworkflow)
| [Source Repo](https://github.com/nickytonline/alfred-workflows/tree/master/workflows) 
| 🍺️ [Nick Taylor](https://github.com/nickytonline)

Download YouTube videos with just a link.

Prerequisites: `youtube-dl` which you can install via [Homebrew](https://brew.sh) (`brew install youtube-dl`)

---


## WIP  

### Brave Browser: v0.3.5 
| [Download Workflow](https://github.com/jun6lee/Useful-Alfred-Workflows/blob/main/Brave-Browser.alfredworkflow)
| [Source Repo](https://github.com/jopemachine/alfred-chrome-workflow) 
| 🍺️ [jopemachine](https://github.com/jopemachine)
| Tweaked for Brave Browser by myself.

Allows you to navigate your bookmarks `chb` / history `chh` /downloads `chd` / and much more.
See the source repo for full instructions. And grab from there if you use Chrome.

![Screenshot](https://github.com/jopemachine/alfred-chrome-workflow/blob/master/imgs/chb.png)

Prerequisites: `Node JS` which you can install via [Homebrew](https://brew.sh) (`brew install node`).

---
