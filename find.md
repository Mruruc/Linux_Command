# 🔍 `find` Command

The `find` command is a powerful utility in for searching files and directories. You can search for files based on various criteria such as name, type, size, or timestamps, and perform operations on the matched files.

find [path...] [expression]


- **`[path ...]`**:  
  Specifies the directory to start searching from. Defaults to the current directory if omitted.

- **`[expression]`**:  
  Specifies the search criteria. This can include options, tests, and actions.

## Paths

- **`.`**:  
  Current directory.

- **`~`**:  
  User's home directory.

- **`/`**:  
  Root directory.

- **`/test1/test2`**:  
  The directory `test1/test2`.

## Search Criteria

### By Name:

- **`-name "file_name"`**:  
  Search with a case-sensitive name.

- **`-iname "file_name"`**:  
  Search with a case-insensitive name.

You can use wildcards (* and ?) for pattern matching. For instance, `-name "*.txt"` matches all files with a `.txt` extension.

### By Type:

- **`-type f`**:  
  Matches only files.

- **`-type d`**:  
  Matches only directories.

- **`-type l`**:  
  Matches only symbolic links.

### By Size:

- **`-size +10M`**:  
  Files larger than 10 MB.

- **`-size -10M`**:  
  Files smaller than 10 MB.

Supported units include `c` (bytes), `k` (kilobytes), `M` (megabytes), and `G` (gigabytes).

### By Modification Time:

- **`-mtime 7`**:  
  Files modified exactly 7 days ago.

- **`-mtime -7`**:  
  Files modified within the last 7 days.

- **`-mtime +7`**:  
  Files modified more than 7 days ago.

### Other Filters:

- **`-empty`**:  
  Matches empty files or directories.

- **`-user username`**:  
  Files owned by a specific user.

- **`-group groupname`**:  
  Files associated with a specific group.

## Actions

Once you've set your starting point and search criteria, you can define what action to take on the matched files/directories:

### Print (default action):

- **`-print`**:  
  Outputs the full file path to the screen.

### Execute a Command:

- **`-exec command {} ;`**:  
  Runs a specified command on each matched file. `{}` serves as a placeholder for the current file. Note: The space between `{}` and `;` is crucial, and some shells might require you to escape the `;` with a `\`.

### Delete:

- **`-delete`**:  
  Removes the matched file.

