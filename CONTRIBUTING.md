# Contribute without losing other work

Use your own clone and Git credentials. The Git host gives readers read access
and only approved contributors write access. Local settings do not enforce this.

1. Fetch the current branch before work and again before pushing.
2. Add a uniquely named note or console-generated record. Keep each focused.
   Do not edit an older knowledge file or update a shared index.
3. Check evidence, scope, format, and whether all readers may see the content.
4. Commit the new files. Merge incoming changes and push normally.
5. If another push won the race, fetch, merge, and retry. Keep both sets of files.
   Never force-push or use automatic "ours" or "theirs" conflict resolution.

Different filenames avoid normal text conflicts. Identical generated records
have identical names and content. If one filename has different content, stop:
this is a collision or an edit to immutable evidence. Preserve both versions,
give the new note a new unique name, and state the correction explicitly.

Contradictory claims are a knowledge issue, not a file conflict. Keep both claims,
their scope, and evidence. Add a resolution only when evidence supports it.

AGENTS.md, README.md, FORMAT.md, CONSUMING.md, SCHEMA.md, SKILLS.md, skill documents,
and this document define shared conventions.
Changes need deliberate review. Automatic learning must not edit them. Resolve
such conflicts manually after checking both changes. Console sync stops and
reports unresolved conflicts rather than discarding content.

Skill changes need deliberate commits. Compare criteria with the specialized
console and personal versions, preserve their files, and keep each standalone
folder usable with its own references. Commit only regular, non-executable
Markdown files: `skills/<name>/SKILL.md` and `skills/<name>/references/<name>.md`.
Use lowercase words and hyphens for names. Automatic sync accepts committed
skills but does not stage, author or install them.

The console commits eligible new notes and records. It refuses tracked edits or
unrelated files and retries rejected pushes up to four times. Offline work stays
local for a later sync. This scheme assumes writers follow the rules. No client
can guarantee safe merges after arbitrary rewrites of files or history.
