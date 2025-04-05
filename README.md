# Horizontal tabs for zen browser
A rice for horizontial tab on the [Zen Browser](https://zen-browser.app/)
## Instructions
* Follow [these](https://docs.zen-browser.app/guides/live-editing) instructions to make a `userChrome.css` file
* Customize your bottom toolbar and bookmark the toolbar however you would like. You will not be able to make changes while in horizontal tabs mode,
* Paste the CSS below in your `userChrome.css` file. Nothing will happen immediately; you must do the next step to make things work correctly.
* go to `about:config` in zen and toggle `zen.tabs.vertical` to false.
* Enjoy your horizontal tabs in Zen! If you find an issue, comment it here until I make a GitHub repository.
## Q & A
Why do my pinned tabs look weird after I pin them: Restart the browser, it is an issue with how the pinned tab is placed, it only gets initialzed in the right space after a restart.
## UI Options
**Not everyone is a fan of a floating UI so this repo has a couple of options (More will come if _you_ make a feature request for it) that will satisfy your UI neeeds while keeping the amazing Zen featre set**

* Chrome UI: add `horizontal.tabs.theme.chrome` to `about:config` and set it to `true`.

## Showcase
* Default Style
![image](https://github.com/user-attachments/assets/0859b501-705e-4ef5-9d67-5559bc58c2e8)
