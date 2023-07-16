# Streams - Deprecated ⚠️

Check out https://github.com/streamlib/streamlib/ 

<hr>

# Streams

Audio and video streams from various sources. Playable through any media player:

```bash
$ mpv "protocol://url.example.com/stream"
$ vlc --open "protocol://url.example.com/stream"
```

[mpv](http://mpv.io) is a fork of mplayer, and is probably your player of choice.
It adds built in support for many streaming sources (youtube, etc).

## Audio

### Radio

#### Israel

 - 88FM - http://iba-s.vidnt.com/iba_radio-88fmMRepeat/_definst_/smil:radio-88fmM.smil/playlist.m3u8
 - 106FM - http://106fm.livecdn.biz:7075/
 - [KZradio](http://kzradio.net) - http://s2.kzradio.net/live/mp3/icecast.audio
 - Galgalatz - http://glzwizzlv.bynetcdn.com/glglz_mp3
 - Reshet Gimmel - http://radiocast-rr-d.vidnt.com/ipbc_IPBCgimmelLAM
 - Kan Bet - https://kanlivep2event-i.akamaihd.net/hls/live/749624/749624/kanbet_mp3/chunklist.m3u8

#### US

 - KEXP - http://live-aacplus-64.kexp.org/kexp64.aac

#### SomaFM

[Support SomaFM](http://somafm.com/support/) - they're awesome and deserve it!

 - Fluid - http://somafm.com/fluid.pls
 - Left Coast 70s - http://somafm.com/seventies.pls
 - ThistleRadio - http://somafm.com/thistle.pls
 - Drone Zone - http://somafm.com/dronezone.pls
 - Groove Salad - http://somafm.com/groovesalad.pls
 - Lush - http://somafm.com/lush.pls
 - Space Station - http://somafm.com/spacestation.pls
 - Digitalis - http://somafm.com/digitalis.pls
 - Underground 80s - http://somafm.com/u80s.pls
 - Indie Pop Rocks! - http://somafm.com/indiepop.pls
 - BAGeL Radio - http://somafm.com/bagel.pls
 - PopTron - http://somafm.com/poptron.pls
 - Folk Forward - http://somafm.com/folkfwd.pls
 - Boot Liquor - http://somafm.com/bootliquor.pls
 - Seven Inch Soul - http://somafm.com/7soul.pls
 - Secret Agent - http://somafm.com/secretagent.pls
 - Sonic Universe - http://somafm.com/sonicuniverse.pls
 - Suburbs of Goa - http://somafm.com/suburbsofgoa.pls
 - Deep Space One - http://somafm.com/deepspaceone.pls
 - DEF CON Radio - http://somafm.com/defcon.pls
 - The Trip - http://somafm.com/thetrip.pls
 - Black Rock FM - http://somafm.com/brfm.pls
 - cliqhop idm - http://somafm.com/cliqhop.pls
 - Dub Step Beyond - http://somafm.com/dubstep.pls
 - Earwaves - http://somafm.com/earwaves.pls
 - Mission Control - http://somafm.com/missioncontrol.pls
 - Illinois Street Lounge - http://somafm.com/illstreet.pls
 - Beat Blender - http://somafm.com/beatblender.pls
 - SF 10-33 - http://somafm.com/sf1033.pls
 - Doomed - http://somafm.com/doomed.pls
 - Covers - http://somafm.com/covers.pls


### WFMU

Via [WFMU listener-supported, non-commercial radio station](https://wfmu.org)

 - WFMU live stream - http://wfmu.org/wfmu.pls
 - giveTheDrummerSome - http://wfmu.org/wfmu_drummer.pls
 - UBUradio - http://wfmu.org/wfmu_ubu.pls
 - Rock 'n' Roll Ichiban - http://wfmu.org/wfmu_rock.pls


### ATC

Via [LiveATC.net](http://www.liveatc.net)

 - Istanbul - http://www.liveatc.net/play/ltba.pls
 - Tokyo Control - http://www.liveatc.net/play/rjtt_control.pls
 - Los Angeles Approach - http://www.liveatc.net/play/klax6.pls
 - San Francisco Tower - http://www.liveatc.net/play/ksfo_twr.pls
 - New York JFK Approach - http://www.liveatc.net/play/kjfk_app_rober.pls


## Video

### TAMI
 - [Science Film Fest](http://telavivmakers.org/index.php/ScienceFilmFest) - http://tami.org.il:8000/sff.ogg

### 7chan

User generated TV channel, more on #7chan

 - 7chan TV - http://radio.7chan.org:8000/CH7

### Public Cams

#### Wazcam 

 - http://live.wazcam.net/live/quds.stream/playlist.m3u8
 - http://live.wazcam.net/live/kana.stream/playlist.m3u8
 - http://live.wazcam.net/live/tamra.stream/playlist.m3u8
 - http://live.wazcam.net/live/shafa.stream/playlist.m3u8
 - http://live.wazcam.net/live/big.stream/playlist.m3u8
 - http://live.wazcam.net/live/city2.stream/playlist.m3u8
 - http://live.wazcam.net/live/yasif.stream/playlist.m3u8
 - http://live.wazcam.net/live/mashhad.stream/playlist.m3u8
 - http://live.wazcam.net/live/reneh.stream/playlist.m3u8

### TV

#### Israel

 - Channel 1 - https://kanlivep2event-i.akamaihd.net/hls/live/747610/747610/master.m3u8
 - Channel 13 - https://besttv1.aoslive.it.best-tv.com/reshet/studio/index.m3u8
   - Requires `Referer` header: `mpv --http-header-fields "Referer: https://besttv1.aoslive.it.best-tv.com/" https://besttv1.aoslive.it.best-tv.com/reshet/studio/index.m3u8`
 - Channel 99 - https://w1.013.gostreaming.tv/Knesset/myStream/playlist.m3u8

#### Other

 - Al-Jazeera - http://aljazeera-ara-apple-live.adaptive.level3.net/apple/aljazeera/arabic/160.m3u8
 - Al-Jazeera English - http://aljazeera-eng-apple-live.adaptive.level3.net/apple/aljazeera/english/appleman.m3u8
 - Al-Mayadeen - [rtsp://livestreaming3.itworkscdn.net/mayadeenlive/mayadsat_240p](rtsp://livestreaming3.itworkscdn.net/mayadeenlive/mayadsat_240p)
