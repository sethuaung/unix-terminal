# Virtual Linux Terminal

![Laptop with Fake Linux Terminal using jQuery Terminal](https://github.com/sethuaung/unix-terminal/blob/master/.github/screenshot.png)


## TODO

- [x] Create Images for directory
- [x] Add a way to load the image in browser and read the file
- [x] Create Web Terminal based on [Fake Linux Terminal](https://codepen.io/jcubic/pen/bzYQNw) (use [LighntingFS version](https://codepen.io/jcubic/pen/vYmjMNd))
- [x] Use [SVG Terminal](https://codepen.io/jcubic/pen/rNYybjr)
- [ ] Work on Some text for the website, add Meta tags, Social Cover Images etc.
- [x] Modify Web Terminal to use LitningFS and FS Images
- [ ] Add authentication based on /etc/passwd file and /etc/shadow (using `$1$` and MD5 hash)
- [x] `[SPIKE]` Persistence of FS (consider save/load buttons - copy to indexedDB)
- [ ] Try to add autologin button that will change hash, so you can refresh the page
- [ ] Implement executable files that will be JavaScript scripts that will run in Web Workers
- [ ] Add stdin/stdout/stderr PIPES to Web Worker API
- [ ] Add way to see the source code of the code (to remove AGPL compliance burden)
- [ ] Implement Bash.js interpreter using [bash-parser](https://www.npmjs.com/package/bash-parser)
- [ ] Try to make Bash.js part of the Image
- [ ] Add env variables e.g. `$PATH` and `PS1`
- [x] `[SPIKE]` ESModules with Service Worker inside Web Worker executable
  - [ ] Shared libraries as ESModules
- [ ] Bash Commands
  - [ ] `cd`
  - [ ] `read`
  - [ ] `echo`
  - [ ] `pwd`
  - [ ] `popd`
  - [ ] `pushd`
  - [ ] `printf`
  - [ ] `logout`
  - [ ] `test`
  - [ ] `source`
  - [ ] `true`
  - [ ] `false`
  - [ ] `alias`
  - [ ] `help`
- [ ] Filestem
  - [ ] `/usr/bin/ls`
  - [ ] `/usr/bin/cat`
  - [ ] `/usr/bin/zip`
  - [ ] `/usr/bin/grep`
  - [ ] `/usr/bin/xargs`
  - [ ] `/usr/bin/head`
  - [ ] `/usr/bin/tail`
  - [ ] `/usr/bin/mkdir`
  - [ ] `/usr/bin/rmdir`
  - [ ] `/usr/bin/mv`
  - [ ] `/usr/bin/rm`
  - [ ] `/usr/bin/less`
  - [ ] `/usr/bin/figlet`
  - [ ] `/usr/bin/download`
  - [ ] `/usr/bin/vi`
  - [ ] `/etc/motd`
  - [ ] `~/.bashrc`
