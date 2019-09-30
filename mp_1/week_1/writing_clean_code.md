Writing readable code is really important! If you’re working on a project with a group, it’s imperative to set coding conventions (rules to writing code) that are mutually understood. One way to set rules for this is by using a “linter”. For this, we will install a python extension in VS Code.

Shift + Command + P, select python linter, pylint, insert settings below into "settings.json" file that pops up

{
    "editor.minimap.enabled": false,
    "python.linting.lintOnSave": true,
    "files.autoSaveDelay": 2500,
    "python.linting.pylintArgs": ["--max-line-length=100"]
}