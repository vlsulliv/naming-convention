[Windows System](#windows-suste) / Root 

File Naming Concentions for Local Files in Windows OS

<div style="text-align: center;"></div>

>Last modified: Jul 2, 2023  

- [File Name Construction](#file-name-construction)
  - [Special Charecters](#special-characters)
  - [Date](#date)
  - [Naming Case](#naming-case)
  - [Increment](#increment)


## File Name Construction

File names will consist of multiple sections and the order of each section should be consistently applied. Sections should be written in the following order:

 1. Date/ date-range
 2. Study title/ Project name
 3. Location of data collection
 4. Version number
 5. Contents of the file
 6. Name/ initials

### Special Characters

Suggested format: W3C/ISO 8601 date standard, which specifies the international standard notation of YYYY-MM-DD or YYYY-MM-DDThh:mm:ss.

Use dashes (-) as deliminator. Periods are allowed in some cases, but their compatibility is system specific. Avoid using special characters, such as: `*`, `:`, `,`, `/`, `<`, `>`, `,`, `|`, `"`, `!`, `?`, `[`, `]`, `;`, `=`, `+`, `&`, `£`, `$`, `€`, `%`, or `,`. Their use may be incompatible on other operating systems and create problems. Only use dash (-) in file names as delimiters to improve readability and OS compatibility. Do not use underscores (_) or spaces - spaces can potentially break URLs (see naming advice from [goole developer docs](https://developers.google.com/style/code-in-text#grammatical-treatment-of-code-elements) for explanation on spaces in files names).

### Date 

Dates will follow the [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601) standards established by the  International Organization for Standardization defining the methods of representing dates and times in textual form. An example of a date/time stamp is `20230910T2253326644Z`, the sections are defined as:

Where:  
   * yyyymmdd = date with YearMonthDate configuration.
   * T = Designates the end of date and the start of time representation. 
   * hhmmss = time with HourMinuteSecond configuration.
   * Z = UTC zone designator
    
### Naming Case

 - Pascal Case: will be used for all folder names (ex: TestNamePattern)
 - Kebab Case: will be used for all file names (ex: auto-clear-mocks)

See drop down for other font casing options.

<details><summary>File Structure</summary>

   * Camel Case:  testNamePattern    
   * Snake Case:  clear_cache  

</details>

### Increment
   *  001 ,  002 ,  003  
   *  Vol. 1 ,  Vol. 2 ,  Vol. 3  
   *  Disk 1 ,  Disk 2 ,  Disk 3  





---


The release notes are divided into the following cate


The following is the syntax for file names. Each presents additional considerations about usibility beyond the local windows file system, which have implications as far as limiting syntax. To keep consistantcy while allowing room for future schema resolutions, the syntax is:

The
Descriptive  
Readable  
Consistent  
Contextual  
Future-friendly  
Extensible  
Reusable  
Brief (short/succinct)  



---
<div style="text-align: center;">

[Back to Top](#back-to-top)

</div>
