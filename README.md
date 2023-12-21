# vim_distros

|name | verdict |  |
|---|---|----|
|vim |  | Ctrl-N for completion menu.|
| vim with codeium plugin | Good based on minimal changes | https://github.com/Exafunction/codeium.vim?tab=readme-ov-file#-getting-started |  
|neovim (nvim) | need to add all language behaviour manually |  |
|lazyvim |  |  |
|lunarvim | more changes than I want (e.g. minibuffer) |  |

### 2023-11 Conclusion
Sadly, it's just not possible to get everything configured to completely replace a Java IDE. Maybe 10 years from now it will be ready for prime time (like Applescript's Javascript replacement), but not yet.

I've taken the out-of-the-box correctness of other IDEs for granted until now.

By all means give it another try when you have the motivation to, but you're going to run into unsolvable issues.


### Config
```
# PATH=/Users/sarnobat/.local/bin/:${PATH}
# PATH=/Volumes/Apps/nvim-macos/bin/:${PATH}
# PATH=${PATH}:${HOME}/Library/Python/3.11/bin
PATH=/Volumes/trash/trash/lsp/jdt/bin/:${PATH}
```

### See also

```lsp_lvim_nvim_examples.sh```
