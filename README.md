# Build & Run C++ in New iTerm Window - Sublime Text
 - Open iTerm: `cp iTermLauncher /usr/local/bin/iTermLauncher`
 - Open Sublime & install `Package Control`  (if you haven't already), then install `PackageResourceViewer` plugin.
 - Open the `Command Palette` (Under Tools tab), type `prv` to bring up the PackageResourceViewer options, select `Open Resource`, then navigate down to C++ and select the `C++ Single File.sublime-build` option. Replace all the contents with given `.sublime-build` file, save it, and you should be all set.
 - Open C++ file, press `⌘  + Shift+ B ` and select suitable option.
 
 # For bits/stdc++.h
  - Run `$ echo "" | gcc -xc - -v -E` to find header file search locations.
  - Go to run of the directories, `$ mkdir bits`
  - Copy https://github.com/gcc-mirror/gcc/blob/master/libstdc%2B%2B-v3/include/precompiled/stdc%2B%2B.h to `bits`.
