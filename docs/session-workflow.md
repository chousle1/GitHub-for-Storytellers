# Maintain Your Notes After a Session

Campaign information changes as the players interact with the world. Characters form new relationships, locations change, factions pursue new goals, and ongoing story threads are resolved or replaced.

This workflow separates two types of information:

- **Session notes** record what happened during a specific game session.
- **Campaign notes** record the current information about characters, locations, factions, story threads, and other parts of the campaign.

## 1. Create a Session Note

After each game session, create a new Markdown file inside the `sessions` folder.

Use a consistent naming pattern so that session files remain in chronological order. For example:

- `session-01.md`
- `session-02.md`
- `session-03.md`

A simple session note might include:

```markdown
# Session 03

## Summary

## Characters

## Locations

## Important Events

## Story Threads
```

The session note does not need to reproduce every event or conversation from the game. Record enough information to help you remember what happened and identify information that may need to be updated elsewhere in the repository.

## 2. Update Existing Notes

Review the events from the session and identify information that has changed.

For example:

- An NPC may have learned new information or changed their relationship with the player characters.
- A location may have been damaged, discovered, or taken over by another faction.
- A faction may have gained or lost an ally.
- A story thread may have progressed or been resolved.
- A significant item may have changed owners.

Update the existing Markdown file for that subject rather than recording the change only in the session summary.

This keeps the individual campaign notes current while the session files preserve a chronological record of how those changes occurred.

## 3. Create Notes for New Information

Create new files when the session introduces characters, locations, factions, items, or story threads that you expect to reference again.

Use the same folder structure and file-naming conventions established in [Organize Your Notes](organize-your-notes.md).

## 4. Connect Related Notes

Add Markdown links when they make information easier to navigate.

For example, a session summary may link to an NPC and location involved in an important event:

```markdown
The party met [Captain Mira Vale](../non-player-characters/captain-mira-vale.md) at [Blackwater Port](../locations/blackwater-port.md).
```

You may also update the NPC or location file with a link back to the relevant session if that connection will be useful later.

## 5. Review Your Changes

Before committing your updates, review the files you changed.

In Visual Studio Code, open the **Source Control** panel. The files you created or edited during the update should appear under **Changes**.

Confirm that:

- New files are stored in the appropriate folders.
- File names follow the same naming conventions as the rest of the repository.
- Markdown links point to the correct files.

## 6. Commit and Sync Your Updates

Stage the files related to the session and create a commit with a short description of the update.

For example:

`Update campaign notes after Session 03`

If you need a refresher, return to [Commit the Change](create-your-repository.md#4-commit-the-change) and [Sync Your Repository with GitHub](create-your-repository.md#5-sync-your-repository-with-github).

A repository's **commit history** is the record of commits that have been made over time. On GitHub, open the repository and select the **commits** link above the file list to view the repository's commit history.

Using one meaningful commit for each session update creates a clear record of how the campaign documentation has changed over time.

## Check Your Work

After synchronizing, open the repository on GitHub and confirm that:

- The new session file appears in the `sessions` folder.
- New campaign notes appear in the correct folders.
- Updated files contain the expected information.
- Links between related Markdown files work correctly.
- The session update appears in the repository's commit history.

Your repository is now ready for the next game session.

## Next Step

Continue to [Troubleshooting](troubleshooting.md) for solutions to common problems involving files, links, synchronization, and repository organization.