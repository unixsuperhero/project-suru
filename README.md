
# The Project Folder Idea

Imagine a folder called projects/.

This folder has a lot of subdirectories.  But each subdirectory is a
self-contained project.

It has directories like:

tmp/
lib/
src/
notes/

It also has what I call a `project` or `start` file.  Which is a file the has
shell cmd snippets that are used often, like how to build a project, or do any
maintenance that has to be ran periodically.  So that whatever command can be
executed in just a few keystrokes from vim.

templates for commonly built files, or sets of files

It also has a list of all the relevant files in the project.  This is so you
can use a regex to search, and `gf` or any equivalent vim mapping to open the
filename under cursor.

It also has some sort of project management, story tracking system.

Whether it is kanban, or anything else, there is some way to track and
prioritize the todo items.


Now take a step back.  Imagine that big projects folder again with all of the
subdirectories.

From the shell you have one command to manage those subdirectories.  Create new
ones, cd into the root of an existing one, run a command from the root of a
project even though your pwd is nowhere close to it.  Run customizable commands
for that specific project such as:
- status
- start server
- tail logs
- git commands
- deploy commands
- etc.

If you use tools like tmux, imagine starting a new tmux session in the root of a
project, having a preset tmux setup for that project.  maybe certain windows
autostart servers, others tail logs, etc.

using simple, mostly out-of-the-box cmds, this is all possible.


