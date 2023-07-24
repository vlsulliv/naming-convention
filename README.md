# naming-convention
local file naming style guide


[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

The file naming convention is a systematic method for naming files that will make them easier to find and retrieve later.

<a href ="top"></a>

## Table of Contents

- [Name Convention](#name-convention)
- [Background](#background)
- [Content](#content)
- [Contribute](#contribute)
- [Resources](#resources)
- [Contact](#contact)
- [License](#license)

## Background

File names are unique entities that identify the its location in a file system. The naming convention is meant to be a systematic method for naming files to make them easier organize. These conventions were created to increase portability, but be aware of limitations on the number of characters and special symbols that your operating system allows.

## Naming Rules

Windows 11 allows the characters A-Z, a-z, 0-9, underscore (\_), period (.), and hyphen (-).

- Names are written in lowercase Latin letters.
- Words are separated by a hyphen (-).
- The block name defines the namespace for its elements and modifiers.
- The element name is separated from the block name by a double underscore (\_\_).
- The modifier name is separated from the block or element name by a single underscore (\_).
- The modifier value is separated from the modifier name by a single underscore (\_).
- For boolean modifiers, the value is not included in the name.

Windows

Windows Explorer does not allow control-characters or \/:\*?"<>|. If you use spaces, you will often have to quote the filename when used from the command line (but GUI apps are unaffected so far as I know). Windows filesystem such as `NTFS` and store the encoding with the filename, but `UTF-16` is standard. Windows uses the two-character combination of CRLF as their line endings in files.

There are OS-specific syntax rules to consider for name specifications. The limit for a windows file name and path is 1024 bytes, 255 characters. Consider your systems [File Specification Syntax](https://www.ibm.com/docs/en/spectrum-protect/8.1.9?topic=parameters-file-specification-syntax) to avoid any issues.

## Content

| `Items`                                                        | `File Contents`                                             | `File Extensions`             |
| -------------------------------------------------------------- | ----------------------------------------------------------- | ----------------------------- |
| [Archive](../../naming-conventions/root/archives/README.md)    | Websites, datasets, backups, resources past retion date     | gz, zip, gzip                 |
| [Music](../../naming-conventions/root/Music/README.md)         | Music, SoundFX, Podcasts, Audiobooks, Recordings, album art | mp3, ogg, aac, jpg            |
| [Documents](../../naming-conventions/root/Documents/README.md) | Notes, Personal documents (Invoices, letters, emails)       | pdf,doc,ppt,xls               |
| [Games](../../naming-conventions/root/Games/README.md)         | Computer, arcade, any-other, extention packs                | exe                           |
| [Images](../../naming-conventions/root/Images/README.md)       | Photography, Art, memes, etc                                | raw, jpg, gif                 |
| [Library](../../naming-conventions/root/Library/README.md)     | Books, writings, scientific papers, articles, magazines     | epub, mobi, pdf               |
| [Software](../../naming-conventions/root/Software/README.md)   | Applications, mobile apps, OS's, Typography                 | exe                           |
| [Video](../../naming-conventions/root/Video/README.md)         | Movies, Shows, Tutorials                                    | mp4, avi, flac, m4a, m4b, ogg |

## Contribute

I am open to any advice, feedback, or remote collaboration that would make this project better.

To clone locally:

    - copy the repo URL `https://github.com/vlsulliv/naming-conventions.git`

    - on your local machine, navigate to the desired project   folder.

    - use cmd prompt or bash shell and enter `git clone https://github.com/vlsulliv/naming-conventions.git`

## Resources

- [dropit](http://www.dropitproject.com/)
- [free file sync](https://freefilesync.org/)

Standards

- [ISO-639-1/B codes](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes)
- [ISO-639-2/B codes](https://en.wikipedia.org/wiki/List_of_ISO_639-2_codes)

Data Management Docs

- [harvard data management](https://datamanagement.hms.harvard.edu/collect/file-naming-conventions)

## Contact

- [Email](mailto:vsulliv@pm.me)
- [Github](https://www.github.com/vlsulliv)
- [Twitter](https://www.twitter.com/visulliv)

## License

[MIT](/LICENSE)

---

[Back to Top](#top)

Made with ❤️ by Vince
