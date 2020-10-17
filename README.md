# MKVToolNix Batch Tool
> An MKVToolNix powered, batch subtitle processing tool to merge subtitle files into videos or remove them from videos.
<br>

## 🛠️ Merging
Ensure the video and subtitle files are arranged similar to the structure below, in this case you would select the `Movies` directory when choosing a source directory in the application. When merging each subdirectory must contain only one **video** file and one **subtitle** file, otherwise the directory will be skipped. Subdirectories may contain other non-video, non-subtitle files, which will be ignored.<br><br>

<pre>
  <code>
    📂Movies
    ┣ 📂Resident Evil (2002) 👈 <b>only one video, and one subtitle file per sub directory</b>
    ┃ ┣ 📺Resident Evil (2002) [1080p].mp4
    ┃ ┗ 📜Resident Evil (2002) [1080p].srt
    ┣ 📂Resident Evil Afterlife (2010)
    ┃ ┣ 📺Resident Evil Afterlife (2010) [1080p].avi
    ┃ ┣ 📜Resident Evil Afterlife (2010) [1080p].ass
    ┃ ┗ 🎨Movie poster.png 👈 <b>extra non-video, non-subtitle files may exist</b>
    ┣ 📂Resident Evil Apocalypse (2004)
    ┃ ┣ 📺Resident Evil Apocalypse (2004) [1080p].mkv
    ┃ ┗ 📜Resident Evil Apocalypse (2004) [1080p].pgs
    ┣ 📂Resident Evil Extinction (2007)
    ┃ ┣ 📺Resident Evil Apocalypse (2004) [1080p].wmv
    ┃ ┗ 📜Resident Evil Apocalypse (2004) [1080p].ssa
    ┣ 📂Resident Evil Retribution (2012)
    ┃ ┣ 📺Resident Evil Retribution (2012) [1080p].ogg
    ┃ ┗ 📜Resident Evil Retribution (2012) [1080p].sup
    ┣ 📂Resident Evil The Final Chapter (2016)
    ┃ ┣ 📺Resident Evil The Final Chapter (2016) [1080p].ogm
    ┃ ┗ 📜Resident Evil The Final Chapter (2016) [1080p].srt
  </code>
</pre>
<br>

## 🗃️ Support

#### Video file types:
* *AVI*, *M4V*, *MKV*, *MOV*, *MP4*, *MPG*, *MPEG*, *OGG*, *OGM*, *WEBM*, *WMV*

#### Subtitle file types:
* *ASS*, *PGS*, *SRT*, *SSA*, *SUP*
<br>

## 🏷️ License
MIT © [iPzard](https://github.com/iPzard/electron-react-python-template/blob/master/LICENSE)