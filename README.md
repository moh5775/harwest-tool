
````markdown
# Submissions

> *Auto-generated with ❤ using [Harwest](https://github.com/nileshsah/harwest-tool)*

## Introduction

A repository to keep track of problem solving practice, containing solutions from platforms:  
**Codeforces**

## Contents

| # | Title | Solution | Tags | Submitted |
|---| ----- | -------- | ---- | --------- |
{submission_placeholder}

## Highlights
* Fully automated collection of all your submissions with minimal effort setup
* Simple and easy to use interface to get you started in minutes
* Extensive traceability for your submissions with reference to the problem, tags, submission date and more
* Single commit for each submission stamped with the original submission date for building rich and accurate contributions graph
* Automated git pushes to the remote repository with every update
* Requires little to no knowledge of operating Git (though learning it is strongly recommended)

## Platforms

Harwest currently has extensive support for the [Codeforces](https://codeforces.com/) platform,  
while integration with various other platforms is still in the kitchen. Contributions are always welcome.

## Installation

You will require `Python 3.5+` along with `pip3` in order to install and use Harwest.  
Refer to the documentation for installing `pip` on [Windows](https://phoenixnap.com/kb/install-pip-windows),  
[Ubuntu/Linux](https://phoenixnap.com/kb/how-to-install-python-3-ubuntu), or  
[macOS](https://docs.python-guide.org/starting/install3/osx/).

The package is available at <https://pypi.python.org/pypi/harwest>  
[![PyPI](https://img.shields.io/pypi/v/harwest.svg)](https://pypi.python.org/pypi/harwest)

Run the following command in the terminal to install the package:

```bash
$ pip3 install harwest
````

## Getting Started

After installing the package, run the following command in the terminal:

```bash
$ harwest
```

In case you're using Harwest for the first time, you'll be greeted with a set of configuration steps to set up the tool.

* **Step \[1]** requires you to select a directory name where all your code submissions will be stored.
  The directory will be created under the same path from where you executed the command.
  If you'd like to set up the directory at some other location, press \<Ctrl>+\<C> to exit, then rerun the command from your desired location.

* **Step \[2]** asks for your full name and email address to be used for git commits.
  **Note:** To have contributions show up on your GitHub contributions graph, use the same email address associated with your GitHub/BitBucket account.

* **Step \[3]** (optional) allows automating git pushes to a remote repository.
  Create an **empty** repository on GitHub or BitBucket (no README, .gitignore, or license), then enter its remote URL here.
  Otherwise, leave blank and push manually later.

Example interaction snippet:

```bash
nellex@HQ:~$ harwest

      __  __                              __
     / / / /___ _______      _____  _____/ /_
    / /_/ / __ `/ ___/ | /| / / _ \/ ___/ __/
   / __  / /_/ / /   | |/ |/ /  __(__  ) /_
  /_/ /_/\__,_/_/    |__/|__/\___/____/\__/

  ==========================================

Hey there! 👋 Looks like you're using Harwest for the first time. Let's get you started 🚀

[1] We'll need to create a directory to store all your files
    The directory will be created as /home/nellex/<your-input>
> So, what would you like your directory to be called? accepted
👍 Alright, so your directory will be created at /home/nellex/accepted

[2] Then let's build your author tag which will appear in your Git commits as:
    Author: Steve Jobs <steve.jobs@apple.com>
> So what would your beautiful (Author) Full Name be? Nilesh Sah
> And of course, your magical (Author) Email Address? nilesh.sah13@gmail.com

[3] Guess what? We can automate the Git pushes for you too! 🎉
   In case you'd like that, then please specify the remote Git Url for an "empty" repository
   It would be somewhat like https://github.com/nileshsah/harwest-tool.git
   But it's optional, in case you'd like to skip then leave it empty and just hit <enter>
> (Optional) So, what would be the remote url for the repository again? https://github.com/nileshsah/accepted.git

 🥳 You rock! We're all good to go now
```

Once the initial setup is complete, you can run:

```bash
$ harwest codeforces
```

to harvest your submissions from Codeforces. The first time, you'll be prompted for your Codeforces handle:

```bash
> So what's your prestigious Codeforces Handle Name? nellex
```

Harwest will scrape all your submissions page-by-page:

```bash
nellex@HQ:~$ harwest codeforces

      __  __                              __
     / / / /___ _______      _____  _____/ /_
    / /_/ / __ `/ ___/ | /| / / _ \/ ___/ __/
   / __  / /_/ / /   | |/ |/ /  __(__  ) /_
  /_/ /_/\__,_/_/    |__/|__/\___/____/\__/

  ==========================================

⛏️ Harvesting Codeforces (nellex) Submissions to /home/nellex/accepted
⌛ Currently scanning page #1: (24/24) Phoenix and Beauty https://codeforces.com/contest/1348/problem/B
Username for 'https://github.com': nileshsah
Password for 'https://nileshsah@github.com':
👌 The updates were automatically pushed to the remote repository
✅ The repository was successfully updated!
```

If scanning stops due to a server error, restart from a specific page:

```bash
$ harwest codeforces --start-page 3
```

## Reconfigure

To restart configuration steps, run:

```bash
$ harwest --init
```

You can also reuse an existing directory created by Harwest for further updates.

## License

MIT License

```

---

Just copy all of this into your `README.md` file.  
If you want, I can also provide the **MIT LICENSE** file content next! Would you like that?
```
