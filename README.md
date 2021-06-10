# VS Windows - Snippet installation guide
- Clone this repository to the directory of your liking here after referenced by `$RepositoryDirectory$`
- Create a hard symlink between your Visual Studio for Windows snippet directory and the VS snippet directory in this repository
    - Copy the path of your snippet directory, the default path is: `%userprofile%\Documents\Visual Studio 2019\Code Snippets\Visual C#\My Code Snippets`
    - Create the symlink with CMD (in administrator mode): `mklink /J "$RepositoryDirectory$\VS-Win-Snippets" "%userprofile%\Documents\Visual Studio 2019\Code Snippets\Visual C#\My Code Snippets"`
    - You are all set.
- Now you can use this or the default snippet folder as you are used to and commit and push local changes, or pull in changes from remote

# Visual Studio shortcuts

## Refactoring (Resharper)
- **Add parameter**: _with cursor near variable press_ `Ctrl` + `R`, `P`
- **Change return type**: _with cursor near method name press_ `Ctrl` + `R`, `S`


## Selection

- `Ctrl` + `Alt` + click : Add a secondary caret
- `Ctrl` + `Alt` + double-click : Add a secondary word selection
- `Ctrl` + `Alt` + click + drag : Add a secondary selection
- `Shift` + `Alt` + . : Add the next matching text as a selection
- `Shift` + `Alt` + ; : Add all matching text as selections
- `Shift` + `Alt` + , : Remove last selected occurrence
- `Shift` + `Alt` + / : Skip next matching occurrence
- `Alt` + click : Add a box selection
- `Esc` or click : Clear all selections

## Move methods / code blocks (Resharper)
`Ctrl` + `Shift` + `Alt` + `↑`/`↓`/`←`/`→`

## Remove/Add lines (Resharper)
- **Remove line:** `Ctrl` + `Shift` + `L`
- **Duplicate line:** `Ctrl` + `D`
- **Add line above:** `Ctrl` + `Enter`
- **Add line below:** `Shift` + `Enter`
