# yt-dl-chapters

Exactly what it says. Downloads a youtube video and splits it into chapters. It looks for a file called CUTS in `$PWD` (can be a copy-pasted comment containing timestamps), else it parses the video's chapter information.

Requires `youtube-dl` to fetch the video, `jq` (parses the video's JSON) and `awk` (parsing the copy-pasted comment in CUTS). The three helper scripts should be in $PATH.
