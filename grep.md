# 🔍 `grep` Command

The `grep` command allows you to search for specific patterns within files. By default, it prints lines containing the pattern.

### `grep [options] pattern [files/directories]`


- **`pattern`**:  
  The text or regular expression you're looking for.

- **`files/directories`**:  
  Specifies where to search. If omitted, `grep` searches the standard input.

## Basic Controls:

- **`-i`**:  
  Perform a case-insensitive search.

- **`-v`**:  
  Invert the search. Show lines that do not match the pattern.

- **`-r` or `-R`**:  
  Recursively search through directories.

## Line Controls:

- **`-n`**:  
  Display the line number along with the matched line.

- **`-l`**:  
  Show only the filenames that contain the pattern.

- **`-L`**:  
  Display filenames that don't have the pattern.

- **`-c`**:  
  Count the number of lines that match the pattern.

## Pattern Controls:

- **`-e pattern`**:  
  Specify the pattern. Useful especially when the pattern starts with `-`.

- **`-f file`**:  
  Take the pattern from a file.

- **`-w`**:  
  Match whole words only.

- **`-x`**:  
  Match the entire line only.

## Context Controls:

- **`-A num`**:  
  Show a specific number of lines after the match.

- **`-B num`**:  
  Show a specific number of lines before the match.

- **`-C num`**:  
  Display a specific number of lines both before and after the match.

## Others:

- **`--color`**:  
  Highlight the matched text. Often enabled by default.

