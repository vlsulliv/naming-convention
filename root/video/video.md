# Videos

Videos will contain movies, downloaded clips, tutorials, etc... Movies directory may include auxillary file types such as movie poster and subtitles (jpg, srt). Directory is structured to comply with PLEX library requirements.
 
## Table of Contents

- [Videos](#videos)
- [Contents](#contents)
- [File Formats](#File-Formats)
- [Naming](#naming)
- [Resources](#resources)

## Contents

| `Category`       | `Description`                                                   |
| ---------------- |  -------------------------------------------------------------- |
| Films            | full length movies and specials e.g comedy specials             |
| ShortFilms       | short films released to broad audience usually under ~20 min    |
| TV Show          | episodic, serial, or limited series television shows            |
| Internet         | video clips downloaded from the web                             |
| Tutorial         | videos that deliver information needed to complete a task       |

## File Formats

**video**: `*.{mp4,avi,flac,m4a,m4b,ogg}`  
**movie poster**: `*.{jpg,png,tbn}`  
**subtitle files** `*.{SRT,SMI,SSA (or ASS)}`

## Naming

- `title` and `show`: are synonymous  
- `year`: sets the release year of the series.
- `pt1`, `pt2`: included for videos series
- `cd1`, `cd2`: included for video series ripped from dvds
- `sp`, `special`: indicating an special number; this is equivalent to ep  
- `s`, `se`, or `season`: indicating a season number.
- `e`, `ep`, or `episode`: indicating an episode number.

**Movies**

- /`Movies`/`MovieName-ReleaseYear`/`MovieName-ReleaseYear`.`ext`

```text
/Movies
    /Avatar (2009)
        /Avatar (2009).mkv
    /Batman Begins (2005)
      Batman Begins (2005).mp4
      Batman Begins (2005).en.srt
      poster.jpg
```
**TV Shows**

- /`TV Shows`/`ShowName-ReleaseYear`/`Season##`/`sXXeXX-EpisodeName.ext`

```text
/TV Shows
   /Doctor-Who (1963)
      /Season 01
         s01e01-An Unearthly Child.mp4
         s01e02-The Cave of Skulls.mp4

   /From the Earth to the Moon (1998)
      /Season 01 (1998)
         s01e01-From the Earth to the Moon.mp4
         s01e02-From the Earth to the Moon.mp4
```

**Tutorial**

- /`Tutorial`/`Topic`/`Description-DownloadDate.ext`

```text
/Tutorial
    /technology
        intro-to-javascript-20010204.mp4
```

## Resources

- [Kodi](https://kodi.wiki/view/Naming_video_files/Movies): file Management  
- [Plex](https://support.plex.tv/articles/categories/media-preparation/): file Management  
- [ISO-639-1/B codes](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes): language codes,  two-letter codes, one per language  
- [ISO-639-2/B codes](https://en.wikipedia.org/wiki/List_of_ISO_639-2_codes):  language codes, three-letter codes

---

<div style="text-align: center;">

[Back to Top](#videos)

</div>
  