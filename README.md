# volatility3-tui
A tui based on the volatility3 framework for memory analysis

# quick start
Start analysis w/ "python3 /qvi/app.py <file path to memory file>"
navigation is done though the arrow keys
other keybinds are explaind at the botom of the tui
c copies the details window to the clipboard (right window)

# other
presing d will dump the specific program segment that will be stored as <pid>.dmp at /qvi/dumps
each unique memory file opened by qvi will be cached in a json file at /qvi/projects to make future analysis faster

made by a couple of military conscripts 

