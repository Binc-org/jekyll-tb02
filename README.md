# Paper

Hello :wave:

Today is November 2026... still learning

This is a basic starter template for creating [Jekyll](https://jekyllrb.com/) sites.


  gem install bundler jekyll

  jekyll new my-awesome-site

  cd my-awesome-site

  bundle exec jekyll serve

# => Now browse to http://localhost:4000
## Getting started

These instructions are for those who intend to use this as a starter template for their own site. They assume that you know how to clone or fork a GitHub repo, check it out to your local computer and get a site running via the command line _(terminal)_.

1. Make a copy of this repo by cloning it locally, or forking it then cloning it locally, or by downloading the source
2. Navigate to this site in your terminal
3. goto open terminal 
4. run `gem install bundler jekyll`
5.   gem install bundler jekyll

6.  jekyll Jekell-tb02

  cd my-awesome-site

  bundle exec jekyll serve

# => Now browse to http://localhost:4000
1. run `bundle exec jekyll serve`
1. Open `http://localhost:4000/`

I had issues with FORKing from Jeremy Jekyll-pages so I am here trying to copy and paste.
Today is Sunday and I will try later to keep building this README and explain...
This is Monday, I ran out of time, took my 2nd shot.

 # fix polling bug gem 'wdm', '>=0.1.0' if Gem.win_platform?




 NEW NEW:

There are two ways to start

Option A: Start a brand-new site from scratch

bash
gem install bundler jekyll       # one-time setup
jekyll new Jekell-tb02           # creates a folder called Jekell-tb02
cd Jekell-tb02                   # go into THAT folder
bundle exec jekyll serve         # start the local server

Then open http://localhost:4000 in your browser.

Option B: Use the starter template repo (what the README is about)

bash
gem install bundler jekyll       # one-time setup
git clone <repo-url> my-site     # copy the template to your computer
cd my-site                       # go into the cloned folder
bundle install                   # install the template's dependencies
bundle exec jekyll serve

Then open http://localhost:4000.

Use one of these, not both. If you cloned the template, skip jekyll new, because the site already exists.

What went wrong in your steps
jekyll Jekell-tb02 is missing the word new. It should be jekyll new Jekell-tb02.
You cd’d into the wrong folder. my-awesome-site is only the example name from the docs. If you named your site Jekell-tb02, run cd Jekell-tb02.
You installed twice. Steps 4 and 5 are the same command. Running it once is enough, and only the first time.
“Open terminal” comes first. You need the terminal open before you can navigate anywhere.
Common errors
command not found: jekyll: Ruby or its gems aren’t set up yet. Install Ruby first. On a Mac, Homebrew Ruby works better than the built-in one.
Errors mentioning webrick (newer Ruby versions): run bundle add webrick, then serve again.
Permission errors on gem install (Mac): don’t use sudo. That usually means you’re on the system Ruby. Switch to a Homebrew Ruby or use a version manager like rbenv.
To stop the server: press Ctrl + C in the terminal.

Once the server is running, edit _config.yml or a page in the folder and refresh the browser to see it change. That’s the easiest way to start learning how Jekyll works. If something fails, paste the error message and I’ll help you read it.

To run code, enable code execution and file creation in Settings → Capabilities.

