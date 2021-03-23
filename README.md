# f_expl

Non-standard Linux/Unix Dependencies: fzf ffmpeg mpv mupdf sxiv vim

Make sure to set EDITOR in your environment, if you wish to use something other than vim. If you keep a list of urls with videos to be played by mpv, put them in a file named "vidoes.list". When you traverse to this file f_expl will open it and you can select the url from there.

Tested on Void (x86_64 {glibc, musl}, x86) and Linux Mint 20

Still under active development. I've just slowed down a bit.

# Format for video.list
https://url.example.com/more/stuff/for/example 'Name of Video'
