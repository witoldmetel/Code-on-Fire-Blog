# My Personal Setup

## Raycast

- [Setup](https://raycastapp.notion.site/Hotkey-56103210375b4fc78b63a7c5e7075fb7)
- [Manual](https://raycastapp.notion.site/Raycast-Manual-d5c85a7694dc4e4088b8b93557ea6d2d)

### Commands

- `fs` - file search
- `checkport` - kill port
- `kill` - kill. process
- `mdn` - MDN docs
- `st` - speedtest
- `gs` - google search
- `smi` - search menu items
- `note` - open floating notes
- `gt` - google translate

## Warp

- [Manual](https://docs.warp.dev/?_cio_id=eac40605ccc201bdd60a)

### Commands

- `alt/command + arrow right/left` - move between words
- `control + shift + }` - active next tab

### Theme 
- monokai_pro_classic.yaml

```
# Accent color for UI elements
accent: '#c0c1b5'
# Terminal background color
background: '#272822'
# Whether the theme is lighter or darker.
details: darker
# The foreground color.
foreground: '#fdfff1'
# Ansi escape colors.
terminal_colors:
  bright:
    black:   '#6e7066'
    red:     '#f92672'
    green:   '#a6e22e'
    yellow:  '#a9dc76'
    blue:    '#66d9ef'
    magenta: '#ab9df2'
    cyan:    '#5ad4e6'
    white:   '#fdfff1'
  normal:
    black:   '#272822'
    red:     '#f92672'
    green:   '#a6e22e'
    yellow:  '#a9dc76'
    blue:    '#66d9ef'
    magenta: '#ab9df2'
    cyan:    '#5ad4e6'
    white:   '#fdfff1'
```

## Setup SSH for GitHub

https://help.github.com/en/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

```
$ git config --global user.name "John Doe"
$ git config --global user.email "john@doe.org"

$ git config user.name
$ git config user.email
```

## VSCode user config (settings.json)
```
{
  "editor.roundedSelection": false,
  "editor.snippetSuggestions": "top",
  "editor.tabSize": 2,
  "editor.fontSize": 14,
  "editor.fontLigatures": true,
  "editor.suggestSelection": "first",
  "editor.gotoLocation.multipleDefinitions": "goto",
  "explorer.openEditors.visible": 1,
  "explorer.autoReveal": false,
  "explorer.confirmDragAndDrop": false,
  "workbench.iconTheme": "material-icon-theme",
  "workbench.colorTheme": "Monokai Classic",
  "workbench.editor.enablePreviewFromQuickOpen": false,
  "workbench.startupEditor": "newUntitledFile",
  "liveServer.settings.donotShowInfoMsg": true,
  "gitlens.advanced.messages": {
    "suppressCommitHasNoPreviousCommitWarning": false,
    "suppressCommitNotFoundWarning": false,
    "suppressFileNotUnderSourceControlWarning": false,
    "suppressGitVersionWarning": false,
    "suppressLineUncommittedWarning": false,
    "suppressNoRepositoryWarning": false
  },
  "gitlens.keymap": "none",
  "todohighlight.keywords": ["todo", "@todo", "fixme", "@fixme"],
  "todohighlight.isCaseSensitive": false,
  "todohighlight.defaultStyle": {
    "color": "white",
    "backgroundColor": "#ffab00",
    "overviewRulerColor": "#ffab00",
    "fontWeight": "bold"
  },
  "breadcrumbs.enabled": true,
  "javascript.updateImportsOnFileMove.enabled": "never",
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "typescript.updateImportsOnFileMove.enabled": "never",
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "eslint.migration.2_x": "off",
  "eslint.enable": true,
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact"
  ],
  "colorize.languages": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact"
  ],
  "git.confirmSync": false,
  "git.autofetch": true,
  "workbench.editor.enablePreview": false,
  "extensions.ignoreRecommendations": true,
  "turboConsoleLog.logMessagePrefix": "",
  "terminal.integrated.defaultProfile.osx": "zsh",
  "terminal.explorerKind": "external",
  "editor.inlineSuggest.enabled": true,
  "editor.linkedEditing": true,
  "git.ignoreMissingGitWarning": true,
  "editor.codeActionsOnSave": {
    "source.fixAll": "explicit"
  },
  "emmet.includeLanguages": {
    "postcss": "css"
  },
  "workbench.colorCustomizations": {
    "sideBarSectionHeader.background": "#0c2c14",
    "tab.activeBackground": "#0c2c14",
    "titleBar.activeBackground": "#0c2c14",
    "statusBar.background": "#0c2c14"
  },
  "prettier.bracketSameLine": true,
  "[prisma]": {
    "editor.defaultFormatter": "Prisma.prisma"
  },
  "editor.formatOnSave": true,
  "window.zoomLevel": 1,
  "window.commandCenter": false,
  "markdown-preview-enhanced.automaticallyShowPreviewOfMarkdownBeingEdited": true,
  "terminal.integrated.env.osx": {},
  "console-ninja.featureSet": "Community",
  "todohighlight.include": [
    "**/*.js",
    "**/*.jsx",
    "**/*.ts",
    "**/*.tsx",
    "**/*.html",
    "**/*.php",
    "**/*.css",
    "**/*.scss"
  ],
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "gitlens.defaultDateShortFormat": "",
  "editor.minimap.enabled": false,
  "gitlens.launchpad.indicator.enabled": false
}
```

### VSCode commands

- `control + shift + p` - show all commands
- `control + p` - open file
- `control + d` - select the same word
- `F2` - rename word
- `option + tilda` - toggle internal terminal
- `control + /` - comment code line
- `control + i` - toggle suggestion
- `control + option + [` - fold
- `control + ,` - open settings
- `command + click` - multiple cursors
- `control + shift + ]` - switch between tabs
- `control + shift + t` - open last closed tabs
- `F12` - find references
- `command + shift + F12` - find references and open it in side bar

## .zshrc
```
alias ls='ls -G'                              # colorize `ls` output
alias zshreload='source ~/.zshrc'             # reload ZSH
alias shtop='sudo htop'                       # run `htop` with root rights
alias grep='grep --color=auto'                # colorize `grep` output
alias ..='cd ..'
alias ...='cd ../..'
alias ....='cd ../../..'
alias less='less -R'
alias g='git'
alias rm='rm -i'                              # confirm removal
alias cp='cp -i'                              # confirm copy
alias mv='mv -i'                              # confirm move
alias cal='gcal --starting-day=1'             # print simple calendar for current month
```

## .gitconfig
```
[alias]
  a = add																		# Add file contents to the index
  ai = add --interactive										# Add modified contents in the working tree interactively to the index.
  ##############
  b = branch
  ba = branch --all                     		# List both remote-tracking branches and local branches.
  bav = branch --all --verbose 							# When in list mode, show sha1 and commit subject line for each head, along with relationship to upstream branch (if any)
  bd = branch --delete 											# Delete a branch. The branch must be fully merged in its upstream branch, or in HEAD if no upstream was set with --track or --set-upstream-to.
  bdd = branch -D 													# Shortcut for --delete --force.
  bm = branch --move												# Move/rename a branch and the corresponding reflog.
  bmm = branch -M 													# Shortcut for --move --force.
  br = branch --remotes 										# List or delete (if used with -d) the remote-tracking branches.
  ##############
  c = commit 																# Record changes to the repository
  ca = commit --all													# Tell the command to automatically stage files that have been modified and deleted, but new files you have not told Git about are not affected.
  cm = commit -m 														# Use the given <msg> as the commit message.
  cam = commit -am 													# Shortcut for --all and -m
  cem = commit --allow-empty -m							# Allows to create a commit without any files modified
  cd = commit --amend												# Replace the tip of the current branch by creating a new commit.
  cad = commit --all --amend								# Shortcut for --amend and --all
  cadne = commit --all --amend --no-edit		# Amends a commit without changing its commit message.
  ##############
  cl = clone 																# Clone a repository into a new directory
  cld = clone --depth 1											# Create a shallow clone with a history truncated to the specified number of commits.
  ##############
  cp = cherry-pick													# Apply the changes introduced by some existing commits
  cpa = cherry-pick --abort									# Cancel the operation and return to the pre-sequence state.
  cpc = cherry-pick --continue 							# Continue the operation in progress using the information in .git/sequencer. Can be used to continue after resolving conflicts in a failed cherry-pick or revert.
  cps = cherry-pick --skip 									# Skip the current commit and continue with the rest of the sequence.
  ##############
  d = diff																	# Show changes between commits, commit and working tree, etc
  di = !"d() { git diff --patch-with-stat HEAD~$1; }; git diff-index --quiet HEAD -- || clear; d" 	# `git di $number` shows the diff between the state `$number` revisions ago and the current state
  dt = difftool															# Show changes using common diff tools
  ##############
  f = fetch 																# Download objects and refs from another repository
  fo = fetch origin 												# Update the remote-tracking branches
  fu = fetch upstream												# Fetch the branches and their respective commits from the upstream repository.
  ##############
  fk = fsck 																# Verifies the connectivity and validity of the objects in the database
  ##############
  g = grep -p																# Print lines matching a pattern
  ##############
  l = log --oneline													# Show commit logs, the commit message is prefixed with this information on the same line.
  lg = log --oneline --graph --decorate			# Draw a text-based graphical representation of the commit history on the left hand side of the output.
  lgs = !"git log --pretty=format:"%C(yellow)%h\\ %ad%Cred%d\\ %Creset%s%Cblue\\ [%cn]" --decorate --date=short" 													# SHA + date + Commit message + author
  lgc = !"git log --pretty=format:"%C(yellow)%h%Cred%d\\ %Creset%s%Cblue\\ [%cn]" --decorate --numstat"																		# SHA + Commit message + author + changed files
  lgt = !"git log --graph --pretty='%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --all" # As tree: SHA + Commit message + Time ago + author
  ##############
  ls = ls-files															# Show information about files in the index and the working tree
  lsm = ls-files --modified									# Show modified files in the output
  lss = ls-files --stage										# Show staged contents' mode bits, object name and stage number in the output.
  ##############
  m = merge 																# Join two or more development histories together
  ma = merge --abort												# Abort the current conflict resolution process, and try to reconstruct the pre-merge state.
  mc = merge --continue											# After a git merge stops due to conflicts you can conclude the merge by running git merge --continue
  mq = merge --quit													# Forget about the current merge in progress. Leave the index and the working tree as-is.
  mm = merge master 												# Merge 'master' branch to the current branch.
  ##############
  o = checkout 															# Switch branches or restore working tree files.
  om = checkout master											# Switch branch to master.
  ob = checkout -b 													# Create and switch to a new branch
  ##############
  pr = prune --verbose --progress						# Prune all unreachable objects from the object database. Report all removed objects. Show progress.
  prn = prune --dry-run											# Do not remove anything; just report what it would remove.
  ##############
  ps = push 																# Update remote refs along with associated objects
  psa = push --all 													# Push all branches (i.e. refs under refs/heads/); cannot be used with other <refspec>.
  psf = push --force												# Usually, the command refuses to update a remote ref that is not an ancestor of the local ref used to overwrite it. This flag disables these checks, and can cause the remote repository to lose commits; use it with care.
  psu = push --set-upstream									# For every branch that is up to date or successfully pushed, add upstream (tracking) reference.
  ##############
  pso = push origin													# `origin` is an alias in the system for a particular remote repository. Can be checked by running `git remote -v`.
  psao = push --all origin									# Same as `push --all` but for origin.
  psfo = push --force origin								# Same as `push --force` but for origin.
  psuo = push --set-upstream origin					# Same as `push --set-upstream` but for origin.
  #############
  psom = push origin master 								# Same as `push origin` but for master branch.
  psaom = push --all origin master					# Same as `push --all origin` but for master branch.
  psfom = push --force origin master				# Same as `push --force origin` but for master branch.
  psuom = push --set-upstream origin master # Same as `push --set-upstream origin` but for master branch.
  #############
  pl = pull 																# Fetch from and integrate with another repository or a local branch.
  plr = pull --rebase 											# When true, rebase the current branch on top of the upstream branch after fetching.
  plv = pull --verbose 											# Pass --verbose to git-fetch and git-merge.
  #############
  plo = pull origin 											  # Same as `pull` but for origin.
  plro = pull --rebase origin								# Same as `pull --rebase` but for origin.
  plom = pull origin master									# Same as `pull origin` but for master branch.
  #############
  plu = pull upstream												# Same as `pull` but for upstream.
  plum = pull upstream master								# Same as `pull upstream` but for master branch.
  plrum = pull --rebase upstream master    	# Same as `pull --rebase` but for upstream and master branch.
  #############
  rb = rebase																# Reapply commits on top of another base tip.
  rba = rebase --abort											# Abort the rebase operation and reset HEAD to the original branch.
  rbc = rebase --continue 									# Restart the rebasing process after having resolved a merge conflict.
  rbi = rebase --interactive                # Make a list of the commits which are about to be rebased. Let the user edit that list before rebasing. This mode can also be used to split commits.
  rbs = rebase --skip 											# Restart the rebasing process by skipping the current patch.
  rbin = "!r() { git rebase -i HEAD~$1; }; r" # Interactive rebase with the given number of latest commits.
  #############
  re = reset																# Reset current HEAD to the specified state
  rh = reset HEAD 													# HEAD is defined explicitly
  reh = reset --hard												# Resets the index and working tree. Any changes to tracked files in the working tree since <commit> are discarded.
  rem = reset --mixed												# Resets the index but not the working tree (i.e., the changed files are preserved but not marked for commit) and reports what has not been updated. This is the default action.
  res = reset --soft                        # Does not touch the index file or the working tree at all (but resets the head to <commit>, just like all modes do). This leaves all your changed files "Changes to be committed".
  rehh = reset --hard HEAD									# HEAD is defined explicitly
  remh = reset --mixed HEAD									# HEAD is defined explicitly
  resh = reset --soft HEAD									# HEAD is defined explicitly
  rehom = reset --hard origin/master				# Throw away all my staged and unstaged changes, forget everything on my current local branch and make it exactly the same as origin/master.
  #############
  r = remote																# Manage set of tracked repositories
  ra = remote add 													# Adds a remote named <name> for the repository at <url>.
  rr = remote remove												# Remove the remote named <name>. All remote-tracking branches and configuration settings for the remote are removed.
  rv = remote --verbose											# Be a little more verbose and show remote url after name.
  rn = remote rename												# Rename the remote named <old> to <new>. All remote-tracking branches and configuration settings for the remote are updated.
  rp = remote prune 												# Deletes stale references associated with <name>. By default, stale remote-tracking branches under <name> are deleted, but depending on global configuration and the configuration of the remote we might even prune local tags that haven't been pushed there.
  rs = remote show 													# Gives some information about the remote <name>.
  rao = remote add origin 									# Add new origin.
  rau = remote add upstream									# Add new upstream.
  rro = remote remove origin								# Remove origin.
  rru = remote remove upstream              # Remove upstream.
  rso = remote show origin									# Show current origin.
  rsu = remote show upstream								# Show current upstream.
  rpo = remote prune origin                 # Prune current origin.
  rpu = remote prune upstream								# Prune current upstream.
  #############
  rmf = rm -f																# Remove files from the working tree and from the index. Override the up-to-date check.
  rmrf = rm -r -f														# Same as above + Allow recursive removal when a leading directory name is given.
  #############
  s = status																# Show the working tree status
  sb = status -s -b													# Same as above + Give the output in the short-format. Show the branch and tracking info even in short-format.
  #############
  sa = stash apply													# Like pop, but do not remove the state from the stash list.
  sc = stash clear													# Remove all the stash entries. Note that those entries will then be subject to pruning, and may be impossible to recover.
  sd = stash drop														# Remove a single stash entry from the list of stash entries. When no <stash> is given, it removes the latest one.
  sl = stash list														# List the stash entries that you currently have.
  sp = stash pop														# Remove a single stashed state from the stash list and apply it on top of the current working tree state, i.e., do the inverse operation of git stash push.
  sps = stash push 													# Save your local modifications to a new stash entry and roll them back to HEAD (in the working tree and in the index). The <message> part is optional and gives the description along with the stashed state.
  spsk = stash push -k											# All changes already added to the index are left intact.
  sw = stash show														# Show the changes recorded in the stash entry as a diff between the stashed contents and the commit back when the stash entry was first created. When no <stash> is given, it shows the latest one.
  st = !git stash list | wc -l 2>/dev/null | grep -oEi '[0-9][0-9]*'
  #############
  t = tag																		# Create, list, delete or verify a tag object signed with GPG.
  td = tag --delete													# Delete existing tags with the given names.
  tl = tag --list														# Show verbose output about tags.
  #############
  w = show                                  # Show various types of objects.
  wo = show --oneline												# This is a shorthand for "--pretty=oneline --abbrev-commit" used together.
  wf = show --format=fuller									# Print more extensive info.
  #############
  aliases = !git config -l | grep alias | cut -c 7- # List git aliases
  branches = branch --all 									# List both remote-tracking branches and local branches.
  remotes = remote --verbose 								# Be a little more verbose and show remote url after name.
  contributors = shortlog --summary --numbered	# List contributors with number of commits
  amend = commit --amend --no-edit					# Amend the currently staged files to the latest commit.
  go = "!f() { git checkout -b \"$1\" 2> /dev/null || git checkout \"$1\"; }; f"	# Switch to a branch, creating it if necessary
  fb = "!f() { git branch -a --contains $1; }; f"																	# Find branches containing commit
  ft = "!f() { git describe --always --contains $1; }; f"													# Find tags containing commit
  fc = "!f() { git log --pretty=format:'%C(yellow)%h  %Cblue%ad  %Creset%s%Cgreen  [%cn] %Cred%d' --decorate --date=short -S$1; }; f"				# Find commits by source code
  fm = "!f() { git log --pretty=format:'%C(yellow)%h  %Cblue%ad  %Creset%s%Cgreen  [%cn] %Cred%d' --decorate --date=short --grep=$1; }; f" 	# Find commits by commit message
  dm = "!git branch --merged | grep -v '\\*' | xargs -n 1 git branch -d"	# Remove branches that have already been merged with master (a.k.a. ‘delete merged’)
```
