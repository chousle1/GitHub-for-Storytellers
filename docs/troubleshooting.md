# Troubleshooting

This section addresses common problems that may occur while creating, organizing, and maintaining your campaign repository.

If a problem involves an advanced Git or GitHub feature that is not covered here, consult the resources listed in the [Overview](overview.md#additional-resources).

## Git Commands Do Not Appear in Visual Studio Code

**Problem:** Options such as **Clone Repository** or other Git commands do not appear in Visual Studio Code.

**Solution:** Confirm that Git is installed on your computer.

Open a terminal in Visual Studio Code and enter:

`git --version`

If Git is installed correctly, the terminal will display the installed version.

If the command is not recognized, install [Git](https://git-scm.com/install/) and restart Visual Studio Code.

Visual Studio Code includes Git integration, but it uses the Git installation on your computer to perform Git operations.

## Git Asks You to Identify Yourself

**Problem:** Visual Studio Code will not complete your first commit because Git does not know your name or email address.

**Solution:** From the Visual Studio Code menu, select **Terminal > New Terminal** and enter:

`git config --global user.name "Your Name"`

`git config --global user.email "your-email@example.com"`

Git uses this information to identify the author of future commits.

If you want GitHub to associate the commits with your account, use an email address associated with your GitHub account.

## My Folder Does Not Appear on GitHub

**Problem:** You created a folder in Visual Studio Code, but the folder does not appear on GitHub after you synchronize the repository.

**Solution:** Add at least one file to the folder.

Git tracks files rather than empty folders. An empty folder may exist on your computer without appearing as repository content on GitHub.

For example, creating:

- `locations/`

will not cause the folder to appear on GitHub by itself.

Once you create a file such as:

- `locations/blackwater-port.md`

the folder and file will appear after you commit and synchronize the change.

## A Markdown Link Does Not Work

**Problem:** Selecting a link leads to the wrong file or produces an error.

**Solution:** Check the file path used in the Markdown link.

A relative link is based on the location of the Markdown file containing the link.

For example, a file stored in `sessions/` can link to an NPC using:

`[Captain Mira Vale](../non-player-characters/captain-mira-vale.md)`

The `..` moves up one folder before entering `non-player-characters`.

Also confirm that:

- The file name is spelled correctly.
- The `.md` extension is included.
- The linked file is stored in the expected folder.
- The link uses the correct number of `../` components.

## An Image Does Not Appear

**Problem:** Markdown displays a broken image symbol or does not display an image.

**Solution:** Check the image path and file name.

For example:

`![Portrait of Captain Mira Vale](../images/captain-mira-vale.png)`

Confirm that:

- The image exists in the expected folder.
- The file name and extension are correct.
- The relative path is correct from the Markdown file containing the image.
- The image file has been committed and synchronized with GitHub.

Images stored only on your computer cannot be displayed to other users viewing the repository on GitHub.

## I Committed My Changes, but They Do Not Appear on GitHub

**Problem:** Your changes disappeared from the **Changes** list in Visual Studio Code after committing, but the GitHub repository still shows the older version.

**Solution:** The commit may exist only in your local repository.

After committing, select **Sync Changes** in the Source Control panel. Return to the repository on GitHub and refresh the page.

Committing records the change locally. Synchronizing sends your local commits to the remote repository on GitHub.

For a refresher, return to [Commit the Change](create-your-repository.md#4-commit-the-change) and [Sync Your Repository with GitHub](create-your-repository.md#5-sync-your-repository-with-github).

## Sync Changes Does Not Finish

**Problem:** Visual Studio Code appears to remain stuck while synchronizing the repository.

**Solution:** Git may be waiting for you to authenticate with GitHub.

Check Visual Studio Code for a sign-in prompt. If none appears, open the **Source Control** panel, select the **...** menu, and select **Show Git Output**. Review the most recent message for an authentication error.

If prompted, sign in to GitHub and try synchronizing again.

## I Created a File in the Wrong Folder

**Problem:** A Markdown file was accidentally created in the wrong location.

**Solution:** Move the file to the appropriate folder in the Visual Studio Code Explorer.

After moving the file, check any Markdown links that point to or from that file. Moving a file changes its path, so existing relative links may need to be updated.

## Check the Basics First

If something in the repository does not appear to work correctly, check the following before making larger changes:

- Save the file in Visual Studio Code.
- Confirm that the file is in the intended folder.
- Check spelling and file extensions.
- Preview Markdown files before committing.
- Confirm that your changes were committed.
- Confirm that your commits were synchronized with GitHub.