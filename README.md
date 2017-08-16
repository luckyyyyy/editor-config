# vscode

```json
{
    "extensions.ignoreRecommendations": false,
    "editor.fontSize": 16,
    "editor.fontWeight": "bold",
    "editor.tabCompletion": true,
    "editor.letterSpacing": 0.1,
    "workbench.iconTheme": "material-icon-theme",
    "editor.cursorStyle": "line-thin",
    "editor.renderWhitespace": "all",
    "window.zoomLevel": 0,
    "emmet.showAbbreviationSuggestions": true,
    "emmet.showExpandedAbbreviation": "always",
    "emmet.includeLanguages": {
            "vue-html": "html",
            "vue": "html"
    }
}
```

# sublime text 3

```json
{
	"caret_style": "phase",
	"color_scheme": "Packages/User/SublimeLinter/Monokai (SL).tmTheme",
	"default_line_ending": "unix",
	"ensure_newline_at_eof_on_save": true,
	"file_exclude_patterns":
	[
		"*.dat",
		"*.key",
		"*.sketch",
		"*.exe",
		".DS_Store",
		"*.psd"
	],
	"folder_exclude_patterns":
	[
		".git",
		".idea",
		".svn"
	],
	"font_size": 16,
	"highlight_line": true,
	"ignored_packages":
	[
		"JavaScript",
		"Markdown",
		"Vintage"
	],
	"theme": "Boxy Yesterday.sublime-theme",
	"theme_accent_green": true,
	"theme_font_md": true,
	"theme_scrollbar_colored": true,
	"theme_sidebar_disclosure": true,
	"theme_size_xs": true,
	"theme_tab_selected_filled": true,
	"theme_tab_selected_overlined": true,
	"trim_trailing_white_space_on_save": true,
	"ui_separator": true,
	"word_wrap": false
}

```

# vim
```vim
" Configuration file for vim
set modelines=0		" CVE-2007-2438

" Normally we use vim-extensions. If you want true vi-compatibility
" remove change the following statements
set nocompatible	" Use Vim defaults instead of 100% vi compatibility
set backspace=2		" more powerful backspacing

" Don't write backup file if vim is being called by "crontab -e"
au BufWrite /private/tmp/crontab.* set nowritebackup nobackup
" Don't write backup file if vim is being called by "chpass"
au BufWrite /private/etc/pw.* set nowritebackup nobackup

set number
set ai                  " auto indenting
set ruler               " show the cursor position
set hlsearch            " highlight the last searched term
set history=1000        " keep 1000 lines of history
syntax on               " syntax highlighting
filetype plugin on      " use the file type plugins
```
