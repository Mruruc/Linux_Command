   ## 📘 `cat` Command

- **`cat filename.txt`**:  
  Display the content of a file.

- **`cat file1.txt file2.txt file3.txt`**:  
  Concatenate the contents of multiple files and display them.

- **`cat file1.txt file2.txt > combined.txt`**:  
  Redirect the combined content of two files into a new file.

- **`cat file2.txt >> file1.txt`**:  
  Append the content of `file2.txt` to `file1.txt` without overwriting the original content.

- **`cat -n filename.txt`**:  
  Display the content of a file with line numbers.

- **`cat -s filename.txt`**:  
  Reduce multiple consecutive blank lines in a file down to a single blank line.

## 🌄 `head` Command

- **`head filename.txt`**:  
  Display the first 10 lines of a file.

- **`head -n 20 filename.txt`**:  
  Display the first 20 lines of a file.

- **`head -c 50 filename.txt`**:  
  Display the first 50 bytes of a file.

## 🌅 `tail` Command

- **`tail filename.txt`**:  
  Display the last 10 lines of a file.

- **`tail -n 20 filename.txt`**:  
  Display the last 20 lines of a file.

## 🔍 `less` Command

- **`less filename.txt`**:  
  Open a file for viewing and navigation. Key commands:

  - `Spacebar`: Scroll down one screen.
  - `b`: Scroll up one screen.
  - `j`: Scroll down one line.
  - `k`: Scroll up one line.
  - `g`: Go to the beginning of the file.
  - `G`: Go to the end of the file.
  - `q`: Quit the `less` viewer.

- **`less +23 filename.txt`**:  
  Open `filename.txt` and jump directly to line 23.

