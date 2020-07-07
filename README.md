# pycharm-cheatsheet
*A simple personal markdown cheatsheet for PyCharm IDE* (Uses custom keymap based on the KDE keymap template)

## Actions
* `Ctrl` + `Shift` + `A` - **Find Action** speed type any action I don't remember shortcut for.
* `Ctrl` + `E` - **Recent Actions** the same dialoque as the *recent files*, also offers recent actions, such as opening a *Run* window or the *Terminal* window. 
  `Ctrl` + `E` and typing `term` + `Enter` is a convenient way to open the terminal. The same with *Console*, *Git*, etc.
* `Shift` + `Shift` - **Find All** this is great - searches through actions, symbols, files... `Shift` + `Shift` and type `term` + `Enter` opens terminal
* `Shift` + `Esc` - **Hide Widow** hides any other window in focus - if I open terminal temporarily as above, this action hides it and gets me back to the *Editor*.

## Navigation
* `Ctrl` + `E` - **Recent Files** opens a dialogue with several recently opened files, always placing the last one on top. Quick `Ctrl` + `E` and `Enter`
  can nicely toggle between two files. As everything, supports speed typing.
* `Ctrl` + `Shift` + `F` - **Find in Path** finds string in path, wherever I'm calling it from.
* `Alt` + `Ctrl` + `Shift` + `N` - **Navigate by Symbol**, also *Find Action* + `symb` will get me there. Can search in project, or in all dependencies.
* `Ctrl` + `Shift` + `N` - **Navigate by File**, also *Find Action* + `n b f` will get me there. Can search in project, or in all dependencies. 
  The speedtyping syntax allows for `dir/fil`.
* `Ctrl` + `B` - jumps to the definition of a datastructure the cursor is on. The same as `Ctrl` + click.
* `Alt` + `Home` - **Navigation Bar** summons a pop-up navigation bar to navigate in the project file structure. Supports everything the project window does - 
  can open any file, can create a new file, delete, rename/refactor, run tests, find in path
* `Shift` + `Home`/`End` - **Jump to the beginning/end of line**
* `Ctrl` + `Home`/`End` - **Jump to the beginning/end of file**
* `Alt` + `Up`/`Down` - **Move up/down (fast)**

## Editor
* `Shift` + `Enter` - **Start New Line** adds a new line below the line the cursor is in.
* `Alt` + `Ctrl` + `Enter` - **Start New Linee Before** adds a new line above the line the cursor is in.
* `Ctrl` + `W` - **Make/Extend Selection** selects word, line, block etc
* `Shift` + `Ctrl` + `W` - **Reduce Selection** drills back down through the ladder of extended selections done by `Ctrl` + `W`
* `Alt` + `Shift` + `Up/Down` - **Move Block** moves selected block up/down.
* `Alt` + `Shift` + `L` - **Reformat Code**
* `Alt` + `Ctrl` + `O` - **Optimise Imports**
* `Alt` + `Enter` - **Show Intention Actions** for any genetorial work the IDE can do for me.
  * Auto-adding imports after typing a function/package
  * Automatically turning `__init__` arguments into instance attributes
  * Correcting typos
  * Converting `from module import class` into `import package` and `module.class`
* `Ctrl` + `Shift` + `T` - **Generate Test** this is super useful, if called from any method or function, it gives a dialogue to generate test function for it.
* `Shift` + `F6` - **Refactor**
* `Ctrl` + `Q` - **Documentation** of the object with cursor on
* `Ctrl` + `P` - **Parameters** of any callable, if cursor inside constructor brackets
* `Alt` + `Right`/`Left` - **Go to Next/Previous Splitter** (this is a custom binding, replacing the *go to next tab*)
* `Ctrl` + `4` - **Close** whatever is open - tab in editor, terminal, run window...

## Running Code
* `Shift` + `F10` - **Runs** the active run configuration
* `Alt Gr` + `F10` - **Select configuration and Run** (this is a custom binding, since the original Shift + Alt + F10 was not registering for some reason)
* `Ctrl` + `Shift` + `F10` - **Runs the context configuration** - relevant to the current code file under focus
  * Run all the tests when focused on tests directory
  * Run all the tests in a file when focused on top of a file
  * Run a single test when focused on it.
