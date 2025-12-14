A Github Pages template for academic websites. This was forked (then detached) by [Stuart Geiger](https://github.com/staeiou) from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/), which is © 2016 Michael Rose and released under the MIT License. See LICENSE.md.

I think I've got things running smoothly and fixed some major bugs, but feel free to file issues or make pull requests if you want to improve the generic template / theme.

### Note: if you are using this repo and now get a notification about a security vulnerability, delete the Gemfile.lock file. 

# Instructions

1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section
1. (Optional) Use the Jupyter notebooks or python scripts in the `markdown_generator` folder to generate markdown files for publications and talks from a TSV file.

See more info at https://academicpages.github.io/

## To run locally (not on GitHub Pages, to serve on your own computer)

1. Clone the repository and made updates as detailed above
1. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
1. Run `bundle clean` to clean up the directory (no need to run `--force`)
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `bundle exec jekyll liveserve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.

## To run locally based on WSL (JR Lin)

1. Install Ubuntu
2. Install jekyll, ref [here](https://jekyllrb.com/docs/installation/windows/)
3. Run `sudo apt-get install libpng-dev` and `sudo apt-get install --reinstall zlibc zlib1g zlib1g-dev` if encounter errors at step 2 or exec cmd `bundle install
4. Clone the repository, and run `bundle install` or `bundle clean` if needed
5. Run `bundle exec jekyll serve`
6. Add `gem “faraday”, “< 1.0”` if needed
7. build and test:
7.1 sudo mount -t drvfs d: /mnt/d (for usb drive only)
7.2 cd /mnt/d/Documents/dev/linjiarui.github.io
7.3 sudo bundle exec jekyll build


## To run locally based on WSL (JR Lin Dec, 2025)

1. Install Ubuntu 22
2. install ruby via rbenv
2.1 install rbenv with ` sudo apt install rbenv`
2.2 Install System Dependencies: exec the following cmds to update and install required packages
sudo apt update
sudo apt install git curl libssl-dev libreadline-dev zlib1g-dev libffi-dev libyaml-dev build-essential
2.3 Clone the repositories
git clone https://github.com/rbenv/rbenv.git ~/.rbenv
git clone https://github.com/rbenv/ruby-build.git ~/.rbenv/plugins/ruby-build
2.4 Add rbenv to your shell's PATH and initialize it:
echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc
echo 'eval "$(rbenv init -)"' >> ~/.bashrc
source ~/.bashrc
2.5 Verify rbenv is set up via `type rbenv` and list available ruby versions via `rbenv install -l`
install ruby-2.7.5 via `rbenv install 2.7.5`, then you need exec `rbenv global 2.7.5` and restart the cmd interface
2.6 related gem and bundle will installed together, or you can change the version of gem or bundle via `gem install gem_name -v 1.1.0` (replace gem_name and 1.1.0 with your desired values)
3. switch to the path via `cd /your/path/here` and exec `bundle intall`
4. exec `sh build_site.sh` to build the site or exec `bundle exec jekyll serve` for testing

## Tips (JR Lin)
1. Do not use `'` in front matter, it causes strange issues.
2. Add new collections: a) add collection name and global config in _config.yml, b) add new collection in navigation.yml if needed, for multilingual support purpose, c) add collection name, permalink, etc. of each item in the collection, d) check layout, include template if needed.
3. Check https://mmistakes.github.io/minimal-mistakes/docs/helpers/ for tutorials
4. always remember to add a white space after character `:` 
5. use .htaccess to redirect url if apache is used, and creating different .htaccess files for subfolders is recommended
6. use Miro video converter to generate videos for iphone and other mobile devices


# Changelog -- bugfixes and enhancements

There is one logistical issue with a ready-to-fork template theme like academic pages that makes it a little tricky to get bug fixes and updates to the core theme. If you fork this repository, customize it, then pull again, you'll probably get merge conflicts. If you want to save your various .yml configuration files and markdown files, you can delete the repository and fork it again. Or you can manually patch. 

To support this, all changes to the underlying code appear as a closed issue with the tag 'code change' -- get the list [here](https://github.com/academicpages/academicpages.github.io/issues?q=is%3Aclosed%20is%3Aissue%20label%3A%22code%20change%22%20). Each issue thread includes a comment linking to the single commit or a diff across multiple commits, so those with forked repositories can easily identify what they need to patch.
