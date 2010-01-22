=== Force Download Wordpress Video Plugin ===
Contributors: daburna, moins52
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=moins52%40yahoo%2efr&item_name=Force%20Download%20Plugin&item_number=Support%20Open%20Source&no_shipping=0&no_note=1&tax=0&currency_code=EUR&lc=US&bn=PP%2dDonationsBF&charset=UTF%2d8
Tags: Youtube, Dailymotion, Google, Facebook, embedding, Video, embed, download, telecharger, MyVideo, Clipfish, Revver, Yahoo!, Brightcove, Aniboom, MSN, Liveleak, Collegehumor, slideshare, guba, GoalVideoz  
Requires at least: 2.0.0
Tested up to: 2.8
Stable tag: 0.1

A Wordpress plugin to embed videos from Youtube, Dailymotion, Google Video and many more... and allow your visitors to download the videos !

== Description ==

A Wordpress plugin to embed **videos** from the sites bellow and allow your visitors to ***download the videos** !

The following sites are supported: (**Youtube**, **Youtube** Playlist, **Dailymotion**, **Google Video**, **Facebook**, MyVideo, Brightcove, Aniboom, 123video.nl, MyspaceTV, Yahoo! Video, Veoh, Wandeo, Glumbert, Gametrailers, Gamevideos, LiveLeak, Sevenload, Clipfish, Break.com, Metacafe, Vimeo, Videotube, Blip.tv, Revver, IFILM, Tu.tv, Grouper, Cellfish.com, Sumo.tv, Last.fm, Vsocial, Teachertube, Slideshare, Reason.tv, ComedyCentral, Jumpcut, MSN, Hamburg1, Mncast, Collegehumor, Megavideo, D1g.com, ReelzChannel, Trilulilu, Funny or die, Generic Flash, Youreporter.it, Clipsyndicate, Mojvideo, GoalVideoz, Guba, Wat.tv, OnSMASH, DotSUB, Current, Screen-o-matic).

Please see the [FAQ](http://wordpress.org/extend/plugins/force-download-wordpress-video-plugin/faq/) for details on how to use it.

== Installation ==

1. Copy the folder `force-download-wordpress-video-plugin` in `/wp-content/plugins/`.
2. Activate the plugin through the `Plugins` menu in WordPress.
3. Visit the `Force Download Plugin Configuration` in the `Plugin` menu.
4. Configure any options as desired
5. That's it!

== Frequently Asked Questions ==

[You can find the freshest instruction here](http://www.force-download.net/page/plugin_wordpress.php?b=2).

###Youtube:###
- every occurence of the expression [youtube id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the youtube id. For the URL 
http://www.youtube.com/watch?v=_2SJwPopFSE, the id part is 2SJwPopFSE

The default width and height is definded in "define("YOUTUBE_WIDTH", 425)" and
"define("YOUTUBE_HEIGHT", 350)". To change the default size, simply edit the
values. Additionally you can add the desired width and height to the expression
seperated by spaces (i.e. [youtube id 300 150].

For the URL http://youtube.com/watch?v=2SJwPopFSE, the id part is 2SJwPopFSE,
so a valid tag would be "[youtube 2SJwPopFSE]" or for a smaller player size then
the default dimensions "[youtube 2SJwPopFSE 210 175]"

###Youtube Playlist:###
- every occurence of the expression [youtubeplaylist id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the youtube playlist id. For the URL 
http://www.youtube.com/view_play_list?p=EF1145687A8B929B, the id part is EF1145687A8B929B

It is possible to change the player size by adding the desired width and height to the expression
seperated by spaces (i.e. [youtubeplaylist id width height].

###Google video:###
- every occurence of the expression [google id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the google video id. For the URL
http://video.google.com/videoplay?docid=6869252560470778648, the id part is 6869252560470778648

###Dailymotion:###
- every occurence of the expression [dailymotion id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the dailymotion id. For the URL 
http://www.dailymotion.com/video/x76263_tuto-forcedownload_lifestyle,
the id is x76263, so a valid tag would be "[dailymotion x76263]".

###Break:###
- every occurence of the expression [break id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the Break id. It is a little bit difficult to get
the id. You will find it, when you copy the video code for an embeded player. Look for this line: 
<param name="movie" value="http://embed.break.com/MjI2NTkx">, there you can find the id: MjI2NTkx  

###Metacafe:###
- every occurence of the expression [metacafe id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the Metacafe id. For the URL
http://www.metacafe.com/watch/427425/boulot/, the id part is 427425

###Vimeo:###
- every occurence of the expression [vimeo id width height] (case unsensitive) will start as
an embedded flash player. Replace "id" with the Vimeo id. For the URL
http://www.vimeo.com/138920, the id part is 138920

###MyVideo:###
- every occurence of the expression [myvideo id width height] (case unsensitive) will start as
an embedded flash player. Replace "id" with the MyVideo id. For the URL 
http://www.myvideo.de/watch/366128, the id part is 366128

###MySpaceTV:###
- every occurence of the expression [myspacetv id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the MYSPACETV id. For the URL 
http://vids.myspace.com/index.cfm?fuseaction=vids.individual&VideoID=11315224, the id part is 11315224

###Yahoo! Video:###
- every occurence of the expression [yahoo id width height] (case unsensitive) will start as
an embedded flash player. Replace "id" with the Yahoo! Video id. It is a little bit difficult to get
the id. You will find it, when you copy the video code for an embeded player. Look for this line:
flashvars='id=3253032&emailUrl=http%3A%2F%2...etc..., there you can find the id: 3253032

###MegaVideo:###
- every occurence of the expression [megavideo id width height] (case unsensitive) will start as
an embedded flash player. Replace "id" with the MegaVideo id. For the URL 
http://www.megavideo.com/?v=Q0G3U6F7, the id part is Q0G3U6F7

###MSN:###
- every occurence of the expression [msn id width height] (case unsensitive) will start as
an embedded flash player. Replace "id" with the MSN id. For the URL 
http://video.msn.com/video.aspx?vid=71e6a055-7b68-4fc3-880a-1bcffe1433b5, the id part is 71e6a055-7b68-4fc3-880a-1bcffe1433b5

###Facebook:###
- every occurence of the expression [FB id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the Facebook id. For the URL 
http://www.facebook.com/video/video.php?v=1036384564453, the id part is 1036384564453

###Flickr Video:###
- every occurence of the expression [flickr id width height] (case unsensitive) will start as
an embedded flash player. Replace "id" with the Flickr id. For the URL 
http://www.flickr.com/photos/25530364@N07/3599198949/in/pool-alongphoto, the id part is 3599198949

###Last.fm:###
- every occurence of the expression [lastfm id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the last.fm id. It is a little bit difficult to get
the id. You will find it, when you copy the video code for an embeded player. Look for this line:
<param name="flashvars" value="embed=true&creator=Kettcar&title=Landungsbr%C3%BCcken+raus&uniqueName=Landungsbr%C3%BCcken+raus&albumArt=http://cdn.last.fm/coverart/130x130/1422004.jpg&album=Du+Und+Wieviel+Von+Deinen+Freunden&duration=257&image=http://panther3.last.fm/storable/videocap/15582/0/original.jpg&FSSupport=true" />
the id is:
embed=true&creator=Kettcar&title=Landungsbr%C3%BCcken+raus&uniqueName=Landungsbr%C3%BCcken+raus&albumArt=http://cdn.last.fm/coverart/130x130/1422004.jpg&album=Du+Und+Wieviel+Von+Deinen+Freunden&duration=257&image=http://panther3.last.fm/storable/videocap/15582/0/original.jpg&FSSupport=trueS

###Clipfish:###
- every occurence of the expression [clipfish id width height] (case unsensitive) will start as
an embedded flash player. Replace "id" with the clipfish id. For the URL
http://www.clipfish.de/channel/253/video/2834485/das-schaeferlied-von-schaefer-heinrich/, the id part is 2834485

###Sevenload:###
- every occurence of the expression [sevenload id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the sevenload id. For the URL
http://sevenload.de/videos/8A6KASF-arif-playback, the id part is 8A6KASF

###Videotube:###
- every occurence of the expression [videotube id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the Videotube id. For the URL
http://www.videotube.de/ci/page/player/527, the id part is 527

###Blip:###
- every occurence of the expression [bliptv id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the Blip.tv id. You will find it, 
when you copy the video code for an embeded player. Look for this line: <embed src="http://blip.tv/play/gvFH8rZBgvNh" 
For the URL http://blip.tv/file/1865111, the id part is gvFH8rZBgvNh 

###Revver:###
- every occurence of the expression [revver id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the Revver id. For the URL
http://one.revver.com/watch/174453, the id part is 174453

###UnCut:###
- every occurence of the expression [uncut id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the UnCut id. For the URL
http://uncutvideo.aol.com/videos/16ea5688332b7df5a5dc5ba6a99f4d3d, the id part is 
16ea5688332b7df5a5dc5ba6a99f4d3d

###Grouper:###
- every occurence of the expression [grouper id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the Grouper id. For the URL
http://grouper.com/video/MediaDetails.aspx?id=1759771&ml=o%3D0%26t%3D1%26fx%3D%26fp%3D2%26fmx%3D3%26rnd%3D3, 
the id part is 1759771

###Liveleak:###
- every occurence of the expression [liveleak id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the Liveleak id. For the URL
http://www.liveleak.com/view?i=8d3_1181986751, the id part is 8d3_1181986751

###IFilm:###
- every occurence of the expression [ifilm id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the IFILM id. For the URL
http://www.ifilm.com/video/2878371, the id part is 2878371

###GameTrailers:###
- every occurence of the expression [gametrailers id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the GAMETRAILERS id. For the URL 
http://gametrailers.com/player/22271.html, the id part is 22271

###GameVideos:###
- every occurence of the expression [gamevideos id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the GAMEVIDEOS id. For the URL  
http://www.gamevideos.com/video/id/13217, the id part is 13217

###Glumbert:###
- every occurence of the expression [glumbert id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the GLUMBERT id. For the URL  
http://www.glumbert.com/media/spidermate, the id part is spidermate

###Wandeo:###
- just copy the code from the box: "on my wordpress blog" e.g. [wandeo 0b61aa57760d51eab7b9a58adc16d0a3]

###Veoh:###
- every occurence of the expression [veoh id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the VEOH id. For the URL 
http://www.veoh.com/videos/v849683cxDDQm7y, the id part is v849683cxDDQm7y

###Tu.tv:###
- every occurence of the expression [tutv id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the Tu.tv id. It is a little bit difficult to get
the id. You will find it, when you copy the video code for an embeded player. Look for this line:
...tutvweb.swf?kpt=aHR0cDovL3d3dy50dS50di92aWRlb3Njb2RpL2MvaS9jaWNsaXN0YS1hYnVzaXZvLmZsdg==&x..., 
there you can find the id: aHR0cDovL3d3dy50dS50di92aWRlb3Njb2RpL2MvaS9jaWNsaXN0YS1hYnVzaXZvLmZsdg
 
###Cellfish:###
- every occurence of the expression [cellfish id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the Cellfish id. For the URL 
http://cellfish.cellfish.com/multimedia/97749, the id part is 97749

###Aniboom:###
- every occurence of the expression [aniboom id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the Aniboom id. For the URL 
http://www.aniboom.com/Player.aspx?v=1905, the id part is 1905

###Brightcove:###
- every occurence of the expression [brightcove id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the Brightcove id. For the URL
http://link.brightcove.com/services/player/bcpid416542555?bctid=24776439001, the id part is
24776439001 -> [brightcove 24776439001]

###123video:###
- every occurence of the expression [123videonl id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the 123video.nl id. For the URL
http://123video.nl/playvideos.asp?MovieID=132273, the id part is 132273

###Sumo.tv:###
- every occurence of the expression [sumotv id] (case unsensitive) will start as
an embedded flash player. Replace "id" with the sumo.tv id. It is a little bit difficult to get
the id. You will find it, when you copy the video code for an embeded player. Look for this line:
<param name="flashVars" value="file=00/01/200710049164669307.flv&autostart=true">there you can find the id:
00/01/200710049164669307

###Vsocial:###
[vsocial id]
URL: http://www.vsocial.com/video/?d=106492 ->id=106492 

###Teachertube:###
[teachertube id]
URL: http://www.teachertube.com/view_video.php?viewkey=2c8b64f1380e2a11d84f  but look here: [flashvideo width="425" height="350" filename="http://www.teachertube.com/flvideo/11926.flv" /] ->id=11926

###Slideshare:###
[slideshare id]
Replace "id" with the corresponding values from the URL of the object. For embedding the presentation at 
http://www.slideshare.net/jboutelle/slidecasting-101 just click on 'Post to Wordpress' and you will get this code
[slideshare id=82836&doc=slidecasting-1013073]

###Comedycentral:###
[comedycentral id]
http://www.thedailyshow.com/video/index.jhtml?videoId=122364&title=meaningful-stuff -> [comedycentral 122364]

###Reason.tv:###
[reason id]
http://reason.tv/video/show/157.html -> [reason 157]

###Jumpcut:###
[jumpcut id width height]
http://jumpcut.com/view/?id=774D8BB8E95911DA897BFEAF976EA1AD -> [jumpcut 774D8BB8E95911DA897BFEAF976EA1AD]

###Collegehumor:###
[collegehumor id width height]
http://www.collegehumor.com/video:1727961 -> [collegehumor 1727961]

###Hamburg1 Video:###
[hamburg1 id width height]
http://www.hamburg1video.de/video/iLyROoaftT81.html -> [hamburg1 iLyROoaftT81]

###Mncast.com:###
[mncast id width height]
the id is in the embed code. search for "movieID". for http://www.mncast.com/?4223906 -> [mncast 10005583920080301233042]

###ReelzChannel:###
[reelzchannel id width height]
http://www.reelzchannel.com/video/32097/indiana-jones-4-trailer -> [reelzchannel 32097]

###D1g.com:###
[d1g id width height]
http://www.d1g.com/video/show/1912587 -> [d1g 1912587]

###Trilulilu:###
[trilulilu id width height]
http://www.trilulilu.ro/keskifa/d219752d57c01e -> [trilulilu d219752d57c01e]

###Funny or Die:###
[funnyordie id width height]
http://www.funnyordie.com/videos/3b1e3750e2 -> [funnyordie 3b1e3750e2]

###Generic Flash:###
[flash id]
http://www.messe-ideen.de/upload/magische-zauberkugel.swf -> [flash http://www.messe-ideen.de/upload/magische-zauberkugel.swf]

###Youreporter:###
[youreporter id]
http://www.youreporter.it/view_video.php?viewkey=dac8bc8ba637133b2c65 -> [youreporter dac8bc8ba637133b2c65]

###Clipsyndicate:###
[Clipsyndicate id width height]
http://www.clipsyndicate.com/publish/video/613132/raw_video_tornado_destroys_iowa_bank?wpid=0 -> [clipsyndicate 613132]

###Mojvideo.com:###
[mojvideo id width height]
http://www.mojvideo.com/video-bmw-club-obsotelje/480f35d6e4c046353a58 -> [mojvideo 480f35d6e4c046353a58]

###GoalVideoz:###
[goalvideoz id width height]
http://www.goalvideoz.com/watch/2674-Portugal-vs-Turkey-2nd-Half-Goals-and-Highlights-Euro-2008/ -> [goalvideoz 2674]

###Guba:###
[guba id width geight]
http://www.guba.com/watch/3000093083?duration_step=0&featured=featuredsportsvids&filter_tiny=0&pp=10&sb=8&set=5&sf=0&size_step=0&o=2&sample=1213474809:9b2e64c91768e700634a0248b8c9ee758ff0bd27 -> [guba 3000093083]

###Wat.tv:###
[wat id width height]
http://www.wat.tv/video/ouverture-mondial-presse-automoto-z9po_z1vx_.html -> You will find the id, when you copy the video code for an embeded player. Look 
for this line: <param name="movie" value="http://www.wat.tv/swf2/313547fagwuFO1645548" /> there you find the id. It is 313547fagwuFO1645548 -> [wat 313547fagwuFO1645548]

###Smotri:###
[smotri id width height]
http://smotri.com/video/view/?id=v630387892f -> [smotri v630387892f] 

###OnSMASH:###
[onsmash id width height]
http://videos.onsmash.com/v/3X8RTKaK6C3hya7q -> [onsmash 3X8RTKaK6C3hya7q] 

###dotSUB:###
[dotsub id width height]
http://dotsub.com/view/7774e495-71c5-4a64-83d9-28675d835d90 -> [dotsub 7774e495-71c5-4a64-83d9-28675d835d90]

###Screencast-o-matic:###
[screencast id width height]
http://www.screencast-o-matic.com/watch/cii3lYtk -> [screencast cii3lYtk]

###Current:###
[current id width height]
http://current.com/items/89891774/supernews_twouble_with_twitters.htm -> [current 89891774]

###Kewego:###
[kewego id width height]
http://www.kewego.de/video/iLyROoaftxTc.html -> [kewego iLyROoaftxTc]
