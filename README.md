# PKM System Development Update 2022-10

The acronym PKM stands for **personal knowledge management**. It is the concept of creating a system that manages information consumed, extracts insights, and provides an environment that allows ideas to be captured an recalled naturally through their context and promotes new ideas to be synthesized.


## To Do's

Main Todo's
1. Extract whiteboard sessions from MS OneNote
2. Document progress in this `README.md` file
3. Push to remote repo


Additional Objectives
- Automate system routines with Apple `launchd` and its compatible daemons defined in `<service-label>.plist`
    - This should be located in either `/User/Library/LaunchAgents` or `/User/Library/LaunchDaemons`
    - The executable's appropriate path is `/usr/local/libexec`
        - Can be symlinked to other path
