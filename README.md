# template-activity-01

## Assignment 01: Set up and prerequisites

1. Git
- Install git.
https://git-scm.com/downloads

- You may see references to the stand alone app for git on your desktop. That's not what we're using for this course.

- Watch the videos in this series that you need to watch (seriously, even if you've been working with git for a while, it's sometimes handy to revisit, e.g., the difference between git and Github). They are on youtube. If you don't have a subscription, it will pop up with short ads. Sorry, but these are really decent videos. There's about 30 min total.

https://www.youtube.com/playlist?list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD

- Follow the instructions to do what the videos walk you through.



2. Data Engineering Jobs

- Google "data engineering jobs"
- Read ads (between 5&10)
- What are companies looking for in skills, experience, competencies?
  * Answer:




3. Submit a PR for this assignment.

Follow the instructions below for GitHub procedures in this class.

4. You should know a few things about Markdown, the markup language that  determines how things look when you view them on the Github web interface. That is what we see when we review your work, so you should always check to see how your `README.me` file looks before you submit. You might check out [this cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) for some pointers.

Markdown is designed to look pretty much in plain text the way that you might guess it would look when made into pretty HTML.

### Here are some basics.

Use `#`, `##`, `###`, and so on to indicate headers. The header above is `###`.

```
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

[This is a link](https://www.google.com)

```

Look like this:

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

[This is a link](https://www.google.com)

#### Formatting Code

Since much of what we'll be doing is showing code and output, it's important to know how to display that such that it is readable.

    Inline `code` has `back-ticks around` it.

Inline `code` has `back-ticks around` it.


Blocks of code can be indicated by indenting with 4 spaces or with three back-ticks (<code>```</code).


    ```sql
    SELECT this, that, the_other
    FROM my_table
    ```

```sql
SELECT this, that, the_other
FROM my_table;
```

    ```
    col1               col2               col3
    fun                dog                cat
    mouse              rat                banana
    ```

```
col1               col2               col3
fun                dog                cat
mouse              rat                banana
```
without the backticks, that sql would look like:

SELECT this, that, the_other
FROM my_table;


and that pretty table would look like this (please don't do this!!):

col1               col2               col3
fun                dog                cat
mouse              rat                banana

---

#### GitHub Procedures

In your Python class you used GitHub, with a single repo for all assignments, where you committed without doing a pull request.  In this class, we will try to mimic the real world more closely, so our procedures will be enhanced. 

Each project, including this one, will have it's own repo.

Important:  In w205, please never merge your assignment branch to the master branch. 

Using the git command line: clone down the repo, leave the master branch untouched, create an assignment branch, and move to that branch:
- Open a linux command line to your virtual machine and be sure you are logged in as jupyter.
- Create a ~/w205 directory if it does not already exist `mkdir ~/w205`
- Change directory into the ~/w205 directory `cd ~/w205`
- Clone down your repo `git clone <https url for your repo>`
- Change directory into the repo `cd <repo name>`
- Create an assignment branch `git branch assignment`
- Checkout the assignment branch `git checkout assignment`

The previous steps only need to be done once.  Once you your clone is on the assignment branch it will remain on that branch unless you checkout another branch.

The project workflow follows this pattern, which may be repeated as many times as needed.  In fact it's best to do this frequently as it saves your work into GitHub in case your virtual machine becomes corrupt:
- Make changes to existing files as needed.
- Add new files as needed
- Stage modified files `git add <filename>`
- Commit staged files `git commit -m "<meaningful comment about your changes>"`
- Push the commit on your assignment branch from your clone to GitHub `git push origin assignment`

Once you are done, go to the GitHub web interface and create a pull request comparing the assignment branch to the master branch.  Add your instructor, and only your instructor, as the reviewer.  The date and time stamp of the pull request is considered the submission time for late penalties. 

If you decide to make more changes after you have created a pull request, you can simply close the pull request (without merge!), make more changes, stage, commit, push, and create a final pull request when you are done.  Note that the last data and time stamp of the last pull request will be considered the submission time for late penalties.

Make sure you receive the emails related to your repository! Your project feedback will be given as comment on the pull request. When you receive the feedback, you can address problems or simply comment that you have read the feedback. 
AFTER receiving and answering the feedback, merge you PR to master. Your project only counts as complete once this is done.

---

