## yimmy theme with mercurial support

A simple two-line theme best displayed on a terminal configured with Solarized
Dark colors.

    user@host ~/c/w/dir (branch *)
    >

![Screenshot](https://cloud.githubusercontent.com/assets/2502736/3245408/32c42cde-f172-11e3-8ba3-912191222a11.png)

### Characteristics

- Standard fish prompt characters: > for user, # for root
- Uses the fish `prompt_pwd`, so paths will be abbreviated
- Uses built-in `__fish_git_prompt` functionality
- Added simple support for mercurial
- Indicates Git work-in-progress (gwip/gunwip) if detected
- Prompt character is colored red if previous command had a non-zero exit
  status
- Includes completmentary `LS_COLORS`

### Requirements

You will need the hg-prompt extension, see http://stevelosh.com/projects/hg-prompt/

### Installation:

- clone the repo somewhere
- copy the files to ~/.oh-my-fish/custom/themes/yimmy-hg (or the name you wish)
- set the theme in ~/.config/fish/config.fish with something like `set fish_theme yimmy-hg`
