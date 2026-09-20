# Overview
GitHub is most commonly associated with software development, but the same features that help developers organize and track files can also be useful for managing story information.

For our purposes, a GitHub repository acts as the central location for a tabletop role-playing game campaign. Instead of keeping character notes, locations, session summaries, and other information across several documents or services, each piece of information can be stored as part of a single organized repository.

This guide will not teach every feature available in GitHub. Instead, it focuses on the small set of features needed to create, organize, connect, and maintain story notes.

## Why Use GitHub for Story Notes?

GitHub provides several features that are useful for long-running campaigns and other story projects.

**Organization:** Files and folders can be organized by various categories, rather than a single document.

**Navigation:** Markdown links allow related information to connect across different folders and files, which you can open with a single click!

**Revision history:** Git records changes over time. If information about a character, location, or other part of the campaign changes, the repository maintains a history of those revisions.

**Portability:** Markdown files are plain-text files rather than content locked inside a specialized campaign-management platform. They can be opened and edited with many different applications.

**Flexibility:** The structure of the repository can change as the campaign grows. New folders, files, and links can be added without requiring a predetermined campaign template.

The goal is not to reproduce every feature available in dedicated campaign-management software. Instead, GitHub provides a lightweight system for organizing and maintaining story information using files that remain easy to access and move.

## Terminology and Basic Concepts
Below are some core terms and concepts used throughout this guide:

**Repository:** A repository is the main "container" for the information on your campaign. It contains the folders and files used to store campaign information and also maintains a history of changes made to those files.

**Folders:** Folders divide information into useful categories. A campaign might include separate folders for characters, locations, factions, sessions, and other types of information.

**Markdown files:** Markdown files are plain-text files that use simple formatting symbols for headings, lists, links, and other common elements. In this system, individual Markdown files can be used for character profiles, location descriptions, session summaries, or other campaign notes.

**Links:** Markdown links connect related files. For example, a session summary can link directly to the characters and locations that appeared during that session. This allows campaign information to function as a connected system rather than a collection of isolated documents.

**Commits:** A commit records a set of changes made to the repository. Commits create checkpoints in the project's history, allowing you to see when information was added or changed.

**Local and remote copies:** When a repository is cloned, a copy exists on your computer while another copy remains on GitHub. You can edit the local files in Visual Studio Code, commit those changes, and then sync them with the copy stored on GitHub.

Together, these features create a simple workflow:

1. Store campaign information in a single repository 
2. Organize notes as Markdown files.
3. Link related information when useful.
4. Update the files as the campaign develops.
5. Commit meaningful changes.
6. Sync those changes with GitHub.

## What This Guide Does Not Cover

GitHub includes many features intended for software development and collaboration, including branches, pull requests, and automated workflows. These features are useful in other contexts but are not necessary for the note-management system described in this guide.

The procedures in this guide focus only on the GitHub and Git features needed to:

- Create and clone a repository.
- Create and organize Markdown files.
- Link related information.
- Commit changes.
- Synchronize those changes with GitHub.

Readers who want a broader understanding of GitHub or Markdown can use the resources below.

## Additional Resources

For more comprehensive instruction on GitHub, Git, Markdown, or Visual Studio Code, see:

- [About repositories](https://docs.github.com/en/repositories/creating-and-managing-repositories/about-repositories)
- [Getting started with writing and formatting on GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github)
- [Commits](https://docs.github.com/en/pull-requests/reference/commits)
- [Source control in Visual Studio Code](https://code.visualstudio.com/docs/sourcecontrol/overview)
- [GitHub Skills](https://skills.github.com/)