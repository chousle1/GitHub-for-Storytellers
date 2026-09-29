# Create and Connect Your Notes
Once your campaign information is organized, you can use links, templates, and images to make individual notes easier to navigate and reuse.

## Link Related Information

Markdown links allow you to connect information stored in different files.

A Markdown link uses the following format:

`[Text the reader sees](path-to-file.md)`

For example, a session note stored in the `sessions` folder could link to an NPC:

`[Captain Mira Vale](../non-player-characters/captain-mira-vale.md)`

The `..` moves up one folder from `sessions`, and the rest of the path identifies the file you want to open.

You do not need to link every mention of a character, location, or faction. Add links when they make related information easier to locate.

## Use Simple Templates for Repeated Notes

Some types of information are easier to maintain when they use a consistent structure.

For example, an NPC file might begin with:

```markdown
# Captain Mira Vale

## Role

## Description

## Goals

## Relationships

## Notes
```

A session file might use:

```markdown
# Session 01

## Summary

## Characters

## Locations

## Important Events

## Story Threads
```

Templates do not need to capture every possible detail. Their purpose is to give repeated notes a predictable structure and reduce the amount of time spent deciding how each new file should be organized.

## Add an Image to Your Repository

Store campaign images in the `images` folder so that they remain organized separately from your Markdown files.

To add an existing image:

1. Open the **Explorer** panel in Visual Studio Code.
2. Locate the `images` folder in your repository.
3. Locate the image on your computer using Windows File Explorer.
4. Drag the image from Windows File Explorer into the `images` folder in Visual Studio Code.

The image should now appear inside the `images` folder in the Explorer panel.

Use clear file names that identify the image, such as:

- `captain-mira-vale.png`
- `blackwater-port-map.jpg`
- `sunken-crown.png`

### Display an Image in a Markdown File

Once the image is stored in the repository, use the following Markdown syntax to display it:

`![Description of the image](path-to-image.png)`

For example, an NPC file stored in `non-player-characters` could display a portrait stored in the `images` folder:

`![Portrait of Captain Mira Vale](../images/captain-mira-vale.png)`

The text inside the brackets describes the image and should briefly explain what the image contains.


Your repository is now ready to store campaign information as the story develops.

## Next Step

Continue to [Maintain Your Campaign After a Session](session-workflow.md) to develop a repeatable process for keeping these notes up to date.