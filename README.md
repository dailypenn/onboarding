# DP Onboarding

Hey There! Welcome to the DP Web Development team. I'm excited to have you on.

There are a few things we need to do before you can get started.



## A. Administrative & Housekeeping Stuff

1. Sign the [DP Staff Registration & License Agreement](http://thedp.com/register) form. From the description:

   > Before you can write a story, shoot a photograph, sell an ad, hand out a paper, or do ANYTHING for The Daily Pennsylvanian, 34th Street, UTB, or any of our print or online publications, you must complete this staff registration form and license agreement. This allows us to put you on appropriate staff contact lists and email listserves; it allows us to maintain a record of your work here for future job references — and to invite you to our annual staff banquet! And the license agreement allows us to publish your work.

   This is purely administrative, but is requried before you can start doing, well, anything. Note that by signing this, you agree to relinquish ownership of all work done for the company (including code, graphics, etc.) to The Daily Pennsylvanian, Inc.

2. Join our [slack team](https://thedpinc.slack.com/signup). You should be able to join with any <samp>@*.upenn.edu</samp> email address.

   - Introduce yourself to @everyone in <samp>#chat-general</samp>!

3. Join the [<samp>dailypenn</samp> Github Org](https://github.com/dailypenn) and get added to the developers team. You may have to bother the current Director of Web Dev. about this…

4. Ask the Andrew if you need a Gryphon login. He will probably say no. Gryphon is the CMS we use.

## B. Technical Setup

This part assumes you have a few things: A computer (Mac, PC, Linux), a text editor (emacs, vim, Atom, Sublime), and basic knowledge of how to navigate using the command line. If you lack any of these things, talk to me. 

#### Tool installation

There are some tools you should definitely install.

>  ⚠️ Since most people seem to be developing on macs, the commands below are for macOS. You may need to substitute `brew` for `apt-get` or `yum` depending on your OS.

5. Update your package manager. For homebrew, `brew update && brew upgrade`, for ubuntu,` apt-get update && apt-get upgrade` should do the trick. This might take a sec.


6. Check if you have `git` installed. If not, install it.

   ```shell
   git --version # -> git version 2.12.2 or "git: command not found"
   brew install git
   ```

7. Check if you have `python` installed. If not, install it.

   ```shell
   python --version # -> Python 2.7.10 or "python: command not found"
   brew install python
   ```

8. Check if you have `node` installed. If not, install it.

   ```shell
   node -v # -> v7.4.0 or "node: command not found"
   brew install node
   ```

9. *Optional:* If you think you will be working on ruby projects, check if you have ruby installed. If not, install it. I recommend checking out [rvm](https://rvm.io) if you need to have multiple ruby versions installed.

   ```shell
   ruby -v # -> ruby x.x.x or "ruby: command not found"
   brew install ruby
   ```

 

#### Cloning and Running Stuff

10. Open a terminal and find a place to keep your DP stuff. 

   ```Shell
   mkdir ~/Documents/DP # or wherever you want
   cd ~/Documents/DP # cd into the folder
   ```

11. Clone the two project page repos. Use SSH! Set up keys if you need to.

   ```Shell
   git clone git@github.com:dailypenn/projects.thedp.com.git && git clone git@github.com:dailypenn/projects.34st.com.git
   ```

   This should be good for most people.

   more to come...







