# File Renaming Script

## Overview

This PowerShell script is designed to help you rename files in a folder using a new naming convention. It allows you to specify both the folder path and the desired naming convention for the files. The script will then rename all the files in the specified folder according to the new naming convention, adding a numerical index to each file's name.

## Usage

1. **Run the Script**
   - Open PowerShell.
   - Navigate to the directory where the script is located, or provide the full path to the script.
   - Execute the script by entering `.\rename-files.ps1` (assuming you saved the script as `rename-files.ps1`).

2. **Follow the Prompts**
   - The script will prompt you to enter the folder path where the files are located.
   - Enter the folder path and press Enter.

3. **Enter the New Naming Convention**
   - The script will then prompt you to enter the new naming convention you want to apply to the files (e.g., 'naming_convention').
   - Enter the new naming convention and press Enter.

4. **Observe Progress**
   - The script will display a progress bar indicating the percentage of completion, along with the number of files that have been renamed out of the total.

5. **Completion Message**
   - Once all files have been renamed, the script will display a completion message.

## Example

Suppose you have a folder named `C:\Documents` containing the following files:
```
file1.txt
file2.txt
file3.txt
```

If you run the script and specify the folder path as `C:\Documents` and the new naming convention as `my_files`, the files will be renamed as follows:
```
my_files_01.txt
my_files_02.txt
my_files_03.txt
```

## Note

- Ensure that the folder path you provide exists, and that you have the necessary permissions to rename files within it.
- The script will add a two-digit numerical index to each file name to ensure uniqueness.
- Be cautious when using this script, especially in folders with many files, as it will rename all files within the specified folder.

## Author

- Eldashjay eldashjay@gmail.com

## License

This script is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
