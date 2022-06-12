# sswb #
====

**S**tupid **S**imply **W**eb **B**rowser - A simply gtk web browser


-----
## How to start ##

**Usage:** sswb <url_to_open>

*Example:* sswb 
  
*Example:* sswb https://www.icapito.it

-----
## Options ##

You can now set your default home page by creating a configuration file in your user config folder: *${HOME}/.config/sswb/options.json*

By default sswb use the following options.json:

```
{
    "home": "http://www.icapito.it",
    "resolution": "800x600",
    "search": "https://www.google.it/search?q=%text%",
    "cookies": "/home/black/.config/sswb/cookies.txt",
    "mimes": [
        "text/*",
        "image/*",
        "video/*",
        "application/ogg"
    ],
    "bookmarks": [
        {
            "name": "iCapito.it",
            "url": "https://www.icapito.it"
        }
    ]
}
```

-----
## Release history ##

*Release:* **220612.1**

*Changes:*

  - Added support for local file read and show (file:// support).

=====

*Release:* 220501.2

*Changes:*

  - Added support for about: home, about: blank, about: config and about: bookmarks links
  - Added support for the search engine
  - Added support for specifying which mime types should not be downloaded
  - Added support for bookmarks
  - All parameters can now be configured directly from the json configuration file in *${HOME}/.config/sswb/* , if the file does not exist it will be created with default parameters
  - Added parallelization of download processes
  
=====

*Release:* 220501.1

*Changes:*

  - Code rewriting and cleaning
  - Added go back, go forward and refresh buttons
  - Added URL bar
  - Added support for cookies
  - Added support for setting the default home page

=====

*Release:* 221112.1

*Changes:*

  - Added support for file downloads
  - Added support for notification in gnome
  - Added support for the F5 hotkey to refresh the page
  

