# rog1

Files for Rick Gilmore's web site on [www.personal.psu.edu](http://www.personal.psu.edu/rog1).

1. Render site within RStudio via `rmarkdown::render_site(encoding = 'UTF-8')`
2. Connect to www.personal.psu.edu/rog1/www
    - Log on to PSU VPN (if off campus)
    - `smb://smb.pass.psu.edu/pass/users/r/o/rog1`
3. Copy local files to remote server
    - `cp -r ~/github/rogilmore/rog1/www/ /Volumes/rog1/www`