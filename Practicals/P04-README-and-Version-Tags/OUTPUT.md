# Sample terminal output – P4

```console
$ git add README.md
$ git commit -m "Add project README"
[main e7f8a9b] Add project README
 1 file changed, 18 insertions(+)
 create mode 100644 README.md

$ git tag -a v1.0.0 -m "First portfolio release"
$ git tag
v1.0.0

$ git show v1.0.0
tag v1.0.0
Tagger: Karthik Swamy
First portfolio release

commit e7f8a9b...
Add project README
```

**Result:** The README is committed and the commit is labelled with the annotated tag `v1.0.0`. The commit hash and tagger details depend on your local Git configuration.

> This is an example terminal transcript, not a recording from your Mac. Run the commands in your own repository to capture your actual output.