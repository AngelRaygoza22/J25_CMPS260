# pwd prints the current working directory.
 # whoami prints the username of the currently logged-in user.

# The semicolon (;) separates commands so ls and date run sequentially.
# When ";" is quoted, it is treated as a literal argument, so ls tries to
# list a file named ";" and date is treated as another argument.

# mkdir -p creates all directories at once, including parent directories.
# ls -R recursively lists all files and subdirectories under data.

# The umask controls default permissions for newly created files.
# After changing the umask, the new file had more restrictive permissions.

# The hard link still works because it points to the same inode.
# The symbolic link breaks because its target file was deleted.

# diff shows line-by-line differences.
# cmp reports the first byte where files differ.

# Pipelines avoid intermediate files, are faster, and reduce disk I/O.

# fgrep treats patterns literally, so it is ideal for searching fixed strings
# containing regex metacharacters.
