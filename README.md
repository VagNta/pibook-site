# Website for Making Interactivity book

This website is served from Netlify and it is based on the [minimal-mistakes theme](https://github.com/mmistakes/minimal-mistakes), ~which is dynamically imported on every build with the [jekyll-remote-theme](https://github.com/benbalter/jekyll-remote-theme) plug-in~

# Installation

1. Fork this repo.
2. Configure the deployment from your netlify (or vercel) account and update your `_config.yml`.
3. Edit the about description and URL on the github repository page to match your own repository settings.

>> If you need to edit files in submodules, then fork them, too, and update your main site repository submodule configuration to point to your own forked submodules. When working with submodules it is strongly advised to work in the command line only and to edit files in the respective submodule repository and not in the submodule folder.

>> Η ιστοσελίδα χρησιμοποιεί την τεχνολογία git submodules (σύνδεσμοι αναφοράς σε εξωτερικά αποθετήρια) η οποία απαιτεί επιπλέον βήματα για τον συντονισμό των επιμέρους φακέλων, [διαβάστε](https://github.blog/2016-02-01-working-with-submodules/) [σχετικά](https://www.atlassian.com/git/tutorials/git-submodule). Συνοπτικά, υπάρχουν επιπλέον εντολές για την αρχικοποίηση και τον συγχρονισμό, όπως `git submodule update --remote --init` και `git submodule update --remote --merge`.

>> Optionally run the make-figures shell script (depends on `pandoc`) to prepare figure captions for the chapters text, which are located in `_includes` folder.

# Contribute to content and to development

For members only
1. Fork sdy60-2024/images and sdy60-2024/_gallery to your account (you will have username/images and username/_gallery) or just create your branch
2. Put two images in the images folder with their thumbnails named image-name and image-name-thumb
3. Create a pull request, one of us will merge your changes.
4. Create an md file for each image in the _gallery folder following the same format of the existing files
5. Create a pull request, one of us will merge your changes
6. Create an md file in the _timeline and _slides folders following the same format of the existing files
7. Commit your changes (I think you can do it as a member, otherwise create a pull request)
8. Remember that events and slides at the bottom of each md file must be an image name from the image folder.
9. If you want to add a new case study you must create a new md file in the _case-study folder using the same format as the existnig files. At the end of that file you must have a link to an md file that should be in the _includes folder that contains the main body of the case study.

You can go a long way just by adding/editing files with the Github web interface, but if you really want to hack the internals of this web site, then you might want to get yourself more familiar with the command line and the [jekyll static web site system](https://jekyllrb.com/). In any case, please respect the following licence.

# License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
