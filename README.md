# yt-clipper

Clip YouTube videos without downloading the entire video using {youtube-dl | yt-dlp} and ffmpeg.

```
usage: yt-clipper -u VIDEO_URL -s HH:MM:SS {-e HH:MM:SS | -d TIME} -o PATH [-f FORMAT | -ff PATH | -y PATH | -h]

  -u  | --url              : URL of the video to clip
  -s  | --start            : Time to begin clipping from [HH:MM:SS]
  -e  | --end              : Time to end the clip [HH:MM:SS]
  -d  | --duration         : Time in seconds to end the clip instead of timecode
  -o  | --output           : Path to output the clip to
  -f  | --format           : Format string for youtube-dl [b]
  -y  | --ytdl-bin         : Specify youtube-dl binary [yt-dlp]
  -ff | --ffmpeg-bin       : Specify ffmpeg binary [ffmpeg]
  -h  | --help             : Shows this message

```
