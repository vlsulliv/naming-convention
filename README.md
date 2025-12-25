# Naming-Convention

Naming convention is a framework for naming personal files and folders to make them easier to organize. Use this guide as a base to decide on what works best for you!

## Table of Contents

- [Naming Convention](#naming-convention) 
- [Background](#background)
- [Folder Names](#folder-names)
  - [Folder Naming Guidelines](#folder-naming-guidelines)
- [File Names](#file-names)
  - [File Naming Guideline](#file-naming-guidelines)
  - [File Name Components](#file-name-components)
- [Technical Restrictions](#technical-restrictions)
  - [Linux](#linux)
  - [Windows](#windows)
  - [Mac](#mac)
- [Resources](#resources)
- [Contact](#contact)
- [License](#license)

## Background

The goal is to provide a consistent file structure that makes files easy to locate while maximizing file portability.

File portability ensures your files can be moved/opened in different operating systems without needing to adjust your file structure; this is achieved by using names that observe OS-specific syntax rules.

Folder directories will remain consistent in this framework, but file name conventions will vary depending on the file type (ex: `.docx`, `mp3`, `mp4` etc...).

## Folder Names

Limit the number of 'top folders' to 10. For naming your 'top folders' and `sub folders` use the following guidelines:

NOTE: using less then 10 allows ability to extend later on.

 #### Folder Naming Guidelines
 - Use all lower case
 - No special characters (ex: `*` `.` `”` `/` `\` `[` `]` `:` `;` `|` `=` `,` `<` `?` `>` `$` `#` `!` `‘` `(` `)` `{` `}`).
 - Snake case: will be used for all directory names (ex: `name_pattern`).
   - Underscore `_` is used to separate words for folder names, while hyphen `-` is used to separate words in file names.

ex: `top folders` structure:  

![top folder tree](src\img\folder-tree.png)

The root folder name is the top folder that contains all folders and files. If files are stored on portable media, the root folder name will have the following format drive letter/name (ex: `F:\my-files`).

Note: arxiv = archive 

## File Names

As previously mentioned, file name conventions will vary depending on the type of file. However, all file names will adhere to the following guidelines:

 #### Files Naming Guidelines
 - Use all lower case.
 - Special characters to avoid (ex: `*` `.` `”` `/` `\` `[` `]` `:` `;` `|` `=` `,` `<` `?` `>` `$` `#` `!` `‘` `{` `}`).
   -  Note: the following special characters will be used for specific file types: `(` `)`
 - Kebab case: will be used for all file names (ex: `name-pattern`).
 - Words are separated by a hyphen (`-`).
 - Use "and" rather than an ampersand unless you’re referencing a brand name (ex: `Procter & Gamble`).
 - Maximum length (with pathname) of 256 characters.
 - Date standard formats, [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601) (`YYYYMMDD` or `YYYY`-`MM`-`DD`).
 - Sequential numbers: increment with leading zeros (ex: `001`,  `002`,  `003`)
 - Versioning: use `v01`, `v02`, `v03` to track document versions

## File Name Components

Components will ensure each file is a unique entity in the file system and provide descriptive information in relation to the content it contains. File names will consist of the following components:

- `date`
- `title`
- `location`
- `version number`
- `increment`
- `extension`

The components included in a file name and their order will vary between directory.

## Technical Restrictions

File and folder naming limits vary across different operating systems. This proposed naming convention obeys most restrictions to allow file use cross-platform. See below for more on OS-specific naming restrictions.

### Linux

- [Linux/Unix](https://www.cyberciti.biz/faq/linuxunix-rules-for-naming-file-and-directory-names/): Rules for file and directory names

### Windows
- [WindowsOS](https://learn.microsoft.com/en-us/windows/win32/fileio/naming-a-file): Naming files, paths, and namespaces

### Mac
- [Mac](https://developer.apple.com/library/archive/documentation/FileManagement/Conceptual/FileSystemProgrammingGuide/FileSystemOverview/FileSystemOverview.html): Apple file system basics

## Resources

 - [Bulk Rename Utility](https://www.bulkrenameutility.co.uk/): Free file renaming software for Windows.
 - [Microsoft Power Tools](https://learn.microsoft.com/en-us/windows/powertoys/): A set of free utilities. For our file renaming purposes - the target utility is **PowerRename**.

## Contact

connect with me!

- email: [vsulliv@pm.me](mailto:vsulliv@pm.me)
- github: [github/vlsulliv](https://www.github.com/vlsulliv)

## License

Created under the [**MIT**](/LICENSE) license:     
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

<div style="text-align: center;">

[Back to Top](#naming-convention)

</div>
