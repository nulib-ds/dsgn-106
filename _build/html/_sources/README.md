# dsgn-106

Ben, this is an Open Educational Resource that is going to be launched for the DSGN 106 class that you may have taken. It is not going to be a textbook *per se,* but it will be a loose collection of readings and videos that the students can use as a reference. I shared a OneDrive folder with you with instructions on how it should be organized. I have started some of them already but things are getting hectic for welcome week so I need some help.

Here is what I need you to do:

For every Word doc in the folder, use pandoc to convert from doc to markdown. Tip: use the option `--wrap=none` to have each paragraph be formatted cleanly.
The structure of the word doc is weird so most paragraphs are in quotes, you will need to remove the `>` thing at the beginning of each paragraph to have it formatted for the web correctly.
Links are weird, so you may have stray characters in links that you have to fix.

Before you start, do some reading on [jupyterbook](https://jupyterbook.org/en/stable/intro.html) to get an understanding of the web tech we are using for this.

Some other tips:

You have to embed videos in a kinda weird way, but it is possible. See the `teamwork-reflections.md` file for an example.
Before you push to main, test the website locally using `jupyter-book build .` in the root directory of the project.

Thanks!
