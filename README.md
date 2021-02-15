# videobox
mirror of hitko videobox plugin for joomla
Videobox - Video and audio player, and gallery for articles - V3.1.0

Usage
Single video:
{videobox}video ID{/videobox}
(video ID is what's coloured blue in the following links: http://www.youtube.com/watch?v=KKWTdt5YW_I&feature=plcp
http://vimeo.com/31778558)

Gallery of videos:
With titles:
{videobox}video ID1|title1|,
video ID2|title2|,
video ID3|title3|,
video ID4|title4{/videobox}

Without titles:
{videobox}video ID1|,video ID2|,video ID3|,video ID4{/videobox}

Video separator can be '|,' or '|,<br />'
Optional video title separator is '|'

Single video inside box:
{videobox}video ID||box=1{/videobox}

You can override default settings for each plugin call separately using the following parameters:

width - width of video player
height - height of video player
t_width - width of thumbnail (gallery and box display only)
t_height - height of thumbnail (gallery and box display only)
break - number of videos per line (gallery only)
pages - number of videos per page (gallery only)
style - custom style for box video containter (box only)
lightbox - use lightbox effect when thumbnail is clicked (gallery and box display only)
button - show play button on thumbnails (gallery and box display only)
play - automatically play video when page is opened (single videos without box display only)
Video offset:
To set player to start video at specific point, for example at 2 minutes 15 seconds, append #time to video ID. Offset time can be in set three different shapes:

#20 - video will start at 0:00:20
#2:20 - video will start at 0:02:20
#1:2:20 - video will start at 1:02:20
Usage of parameters:
{videobox}video ID or videos#offset||width=600,height=450,t_width=215{/videobox}

Further information and support: Videobox
