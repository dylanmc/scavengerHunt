# Scavenger Hunt
This is a component of a scavenger hunt activity for learning your way around Unix, git, archive formats, etc.

To get started, you'll see that this repository contains a file ending
in .tar

Tar is the classic Unix archiving program. It's short for "Tape ARchive". Tapes
were (and in some places still are) the primary archive solution for bulk
storage. Tapes are only barely random access devices, so traditional file
systems don't work well for them (we'll learn more about this later in the
Semester). So the Tar format is, in effect, the file system for tapes, and now
in the 21st century, for bundling multiple files into one file.

```
$ man tar
```

will tell you how to use the tar command to unpack a tar file (usually
called a "tarball" because it sounds funnier).
