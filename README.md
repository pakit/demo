## Demo For Pakit

This repo does nothing but hold a gif.

## Making
To Record:
https://github.com/MaartenBaert/ssr

To Grab Screens:
`mplayer -ao null demo.mkv -vo jpeg:outdir=/tmp/demo`

To Make Intermediary Gifs (limit to 1000)
`convert -fuzz 4% -layers Optimize -delay 2 [files] out.gif`

To Concatenate Gifs:

`gifsicle --colors 256 out1.gif out2.gif out3.gif out4.gif out5.gif > comb.gif`
