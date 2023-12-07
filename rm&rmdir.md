## 🗑 `rmdir` Command

- **`rmdir directory_name`**:  
  Removes an empty directory. If a directory is not empty, `rmdir` will display an error and won't remove it.

## 🗑 `rm` Command

### Removing Files:

- **`rm filename`**:  
  Removes a specified file.

### Removing Directories:

- **`rm -r directory_name`**:  
  Removes a directory and its contents recursively.

- **`rm -rf directory_name`**:  
  Forcefully removes a directory and its contents recursively without asking for confirmation. (This will ignore nonexistent files and arguments, so use with caution!)

### Verbosity:

- **`rm -v filename`**:  
  Explains what is being done during the removal process.

### Safe Removal:

- **`rm -i`**:  
  Prompts before every removal. This can help prevent accidental deletions.

