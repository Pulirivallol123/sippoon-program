# no .gita files
*.gita
# but do track lib.gita, even though you're ignoring .gita files above
!lib.gita
# only ignore the root TODO file, not subdir/TODO
/TODO
# ignore all files in the build/ directory
build/
# ignore doc/notes.gittxt, but not doc/server/arch.gittxt
doc/*.gittxt
# ignore all .gittxt files in the doc/ directory
doc/**/*.gittxt