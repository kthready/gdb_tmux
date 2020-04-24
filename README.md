# gdb_tmux
gdb visual tool

Install:
1. Put dbinit to ~/.gdbinit.d/dbinit
2. Put tmux.gdb.conf to ~/.tmux.gdb.conf
3. Install gdb dashboard(https://github.com/cyrus-and/gdb-dashboard):

wget -P ~ https://git.io/.gdbinit

4. Run debug to start

Optional:
There's a patch to official gdb dashboard .gdbinit:
1. Remove display label for each Module
2. Add indicator '>' on current line
3. For no source code assembly, still always put current line in the
   middle, to show nearby instructions
4. Some other slight change to satify me

![image](https://user-images.githubusercontent.com/5469646/80116084-1c177f00-85b8-11ea-946e-dc87fff61dce.png)
