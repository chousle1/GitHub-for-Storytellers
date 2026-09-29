# Organize Your Notes

Once your repository is created, the next step is deciding how campaign information will be organized.

The goal is not to create a folder for every possible type of information. The goal is to make important notes easy to locate.

This guide uses a small set of folders based on information that Game Masters typically need to track during a campaign.

## Create Your Folder Structure

Your repository will contain folders for the major types of information you need to track. These folders should be created at the top level of the repository, alongside `README.md`.

### Create the folders in Visual Studio Code

1. Open the **Explorer** panel on the left side of Visual Studio Code. ![Explorer Icon](images/explorer-icon.PNG)

2. Locate the name of your repository at the top of the Explorer panel.

3. Select the "New Folder..." button next to the repository name so that you are creating new folders at the top level of the repository. The icon looks like a folder with a plus sign.

4. Enter:

   `player-characters`

5. Press **Enter** to create the folder.

6. Repeat the process to create the following folders:

   - `non-player-characters`
   - `locations`
   - `factions`
   - `story-threads`
   - `setting-and-lore`
   - `sessions`
   - `items`
   - `images`

When finished, the Explorer panel should contain the following folders and files:

- `player-characters/`
- `non-player-characters/`
- `locations/`
- `factions/`
- `story-threads/`
- `setting-and-lore/`
- `sessions/`
- `items/`
- `images/`
- `README.md`

This structure is intended as a starting point rather than a complete list of everything a Game Master may need to track. Add, remove, or rename folders to match the needs of your campaign.

>Folders can contain additional folders when a category becomes too large to manage easily.
>To create a subfolder in Visual Studio Code, select the folder that will contain it, then select the **New Folder** icon and enter the new folder name.
>For example, a campaign with many locations might eventually use:
>- `locations/`
>   - `cities/`
  >   - `dungeons/`
  >   - `wilderness/`

> **Why aren't my empty folders appearing on GitHub?**  
> Git tracks files rather than empty folders. A newly created folder may appear in Visual Studio Code but will not appear in Source Control or on GitHub until it contains at least one file. This is normal. Once you create a Markdown note inside the folder, the folder will be included with that file when you commit and sync your changes.

## Decide What Belongs in Each Folder

Each folder should represent a recognizable type of campaign information.

**`player-characters/`**  
Store information about the player characters, including backgrounds, important relationships, goals, or information that has developed during play.

**`non-player-characters/`**  
Store individual notes about recurring or important NPCs.

**`locations/`**  
Store information about cities, settlements, buildings, dungeons, landmarks, or places the Player Characters have been that are important to the campaign.

**`factions/`**  
Store information about organizations, governments, guilds, families, religious groups, or other groups that influence the story.

**`story-threads/`**  
Track ongoing conflicts, mysteries, objectives, plots, or unresolved situations. "Story threads" is intentionally broad so the folder can work for campaigns that do not use traditional quests.

**`setting-and-lore/`**  
Store information about the larger setting that does not belong to a specific character, location, or faction. This may include history, cultures, religions, cosmology, political systems, or other worldbuilding information.

**`sessions/`**  
Store notes or summaries from individual game sessions. These files provide a chronological record of what has happened during the campaign.

**`items/`**  
Store information about significant objects such as artifacts, named weapons, important documents, or plot-related equipment.

**`images/`**\
Images may be useful for character portraits, maps, important items, faction symbols, or other visual information.

## Create Markdown Files

Each individual topic in your repository will be stored as a Markdown file.

To create a Markdown file in Visual Studio Code:

1. Open the **Explorer** panel. ![Explorer Icon](images/explorer-icon.PNG)
2. Select the folder where you want to create the note.
3. Hover over the folder name and select the **New File** icon.
4. Enter a descriptive file name followed by `.md`.

   For example:

   `captain-mira-vale.md`

5. Press **Enter**.

Visual Studio Code will create the file inside the selected folder and open it in the editor.

The `.md` extension identifies the file as Markdown.

> ### Important Note: Create One File for One Topic
> Whenever possible, create a separate Markdown file for each topic instead of storing several unrelated pieces of information in one document.

## Use Consistent File Names

Use clear and predictable file names throughout the repository.

This guide recommends:

- Use lowercase letters.
- Separate words with hyphens.
- Use names that clearly identify the subject.
- Avoid vague names such as `notes.md` or `important.md`.

For example:

```text
captain-mira-vale.md
blackwater-port.md
session-01.md
the-missing-caravan.md
```

Consistent file names make the repository easier to scan and make links between files easier to create.
Continue to [Create and Connect Your Notes](create-and-connect-your-notes.md) to learn how to link related information, use templates, and add images to your campaign notes.