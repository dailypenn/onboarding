# DP Onboarding

Hey there! Welcome to the DP Web Development team. We're excited to have you on.

There are a few things we need to do before you can get started.

## A. Administrative & Housekeeping Stuff

1. Sign the [DP Staff Registration & License Agreement](http://thedp.com/register) form. From the description:

   > Before you can write a story, shoot a photograph, sell an ad, hand out a paper, or do ANYTHING for The Daily Pennsylvanian, 34th Street, UTB, or any of our print or online publications, you must complete this staff registration form and license agreement. This allows us to put you on appropriate staff contact lists and email listservs; it allows us to maintain a record of your work here for future job references — and to invite you to our annual staff banquet! And the license agreement allows us to publish your work.

   This is purely administrative, but is required before you can start doing, well, anything. Note that by signing this, you agree to relinquish ownership of all work done for the company (including code, graphics, etc.) to The Daily Pennsylvanian, Inc.

2. Join our [slack team](https://thedpinc.slack.com/signup). If you have a `@thedp.com` email, you can join right away. Otherwise, you'll need an invite. As the Director of Web Development for this.
   - You'll automatically be added to <samp>#announcements</samp> and <samp>#chat-general</samp>, but make sure to also join <samp>#dept-web</samp> and look through the other channels to see if you're interested in any of them!

3. Join the [dailypenn Github organization](https://github.com/dailypenn) and get added to the developers team. You may have to bother the current Director of Web Development about this.

4. Ask the Director of Web Development if you need a login for our CMS, CEO. (The answer is probably no, but check anyway.)

## B. Technical Setup

This part assumes you have a few things: a computer (Mac, PC, Linux), a text editor (emacs, vim, Atom, Sublime), and basic knowledge of how to navigate using the command line. If you lack any of these things, talk to the Director of Web Development.

#### Tool installation

There are some tools you should definitely install.

>  ⚠️ Since most people seem to be developing on Macs, the commands below are for macOS. You may need to substitute `brew` for `apt-get` or `yum` depending on your OS.

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

9. If you think you will be working on Ruby projects (like Events@Penn or BYOPhilly), check if you have Ruby installed. If not, install it. We recommend checking out [rvm](https://rvm.io) if you need to have multiple Ruby versions installed.

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

11. Clone the repos you'll be working on. Use SSH! (If you don't already use SSH, follow the steps [here](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/) to generate keys, and then [here](https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/) to add your public key to your GitHub account.)

If you're on the project pages team, you'll clone these repos:

   ```Shell
   git clone git@github.com:dailypenn/projects.thedp.com.git
   git clone git@github.com:dailypenn/projects.34st.com.git
   ```

 Talk to the Director of Web Development if you're not sure which repos to clone.
