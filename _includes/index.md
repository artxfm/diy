

## Build Your Own Damn Internet Radio Station

Spin records, interview celebrities, the sky is the limit.  Here's how
**ARTxFM** did it.

### The Overview

* You will probably want **something to play music on**. For example a
  record player or CD player or iPod.
* You will probably want a **microphone** so you can expound on the many
  virtues of German prog-rock to your adoring fans.  You may want **an
  additonal microphone** so that you can interview guest celebs.
* You will need some **headphones** so that when you are using the
  microphone you do not generate feedback.
* Since you will have several audio sources, you will need some sort of
  **mixer**. The mixer will allow you to select which source is going out to
  the interwebs (formally known as "the air").
* You will need **a computer** which will run special software that sends
  the audio to the interwebs.
* You will need an **internet connection**!
* You will need to pay a monthly subscription to make a music stream
  available on the internet.

### Schematic

<pre>
 MIC   RECORD_PLAYER  CD_PLAYER
  |          |           |
  \          |          /
    \        |        /
      \      |       /
       +-----+------+     +----------+
       |    MIXER   |---->| SPEAKERS |
       +-----+------+     +----------+
             |
             |
             |
       +-----+------+                    +-------------------+
       |  COMPUTER  |----->(internet)--->| STREAMING SERVICE |
       +------------+                    +-------------------+
                                           |         |      
                                           |         |       
                                           \/        \/    
                                        listener  listener ...
</pre>


### The Details

1.  Obtain some record players, a cd player, iPod, laptop with
[Spotify](http://spotify.com) subscription, or what have you.

2. Note if you are using record players you will need phono pre-amps for
them.  Something simple like the
[PylePro PP999](http://www.amazon.com/Pyle-PP999-Phono-Turntable-Pre-Amp/dp/B00025742A#)
will work.

3. Get a mic. A traditional vocal might migh be an
[RE20](http://www.sweetwater.com/store/detail/RE20/), at **ARTxFM** we
use an [MD421](http://www.sweetwater.com/store/detail/MD421). Note that
an [SM58](http://www.sweetwater.com/store/detail/SM58) will work great.

4. You will probably want a nice mic holder. Something like the
[Rode PSA1](http://www.sweetwater.com/store/detail/PSA1Rode).

2.  Get some sort of mixer. We have a fancy pants
[AIR-1 Radio Console](http://www.audioartsengineering.com/index.php/air-1-radio-console-overview). The
benefit of getting a radio specific mixer like the AIR-1 is that the
features you need are all there.  You can get something simpler/cheaper,
but you will need to do more messing about.  Check out mixers from
Mackie, Allen & Heath, and Behringer.  Just make sure you have enough
**stereo** inputs for the signals you are trying to route. For example,
if you have two record players, a CD player, and an iPod then you need 4
stereo inputs.  The
[Mackie 1202vlz4](http://www.sweetwater.com/store/detail/1202VLZ4) has 4
line-level stereo inputs, for example.

3. You will want some speakers so that you can kick out the jams in your
control room. You can just use headphones if you like. If you are
connecting to a mixer, you will need powered spearkers (or find an
unused amplifier or reciever).

4. Don't forget headphones.  Most mixers just have one headphone
output. If you want your interviewees to be able to hear themselves,
then you need to get a [headphone distribution amplifer](http://www.bhphotovideo.com/c/product/373745-REG/Behringer_HA400_HA_400_Headphone.html/prm/alsVwDtl). And some additional headphones.

2.  Get a computer. We use a [Mac Mini](http://www.apple.com/mac-mini/),
but you can use any damn computer you want.  However, the rest of this
tutorial will assume a mac.

3.  Sign up for a [shoutcast streaming plan at Via Streaming](http://www.viastreaming.com/shoutcast).

4. Install [Nicecast](https://www.rogueamoeba.com/nicecast/) on the mac
you will use to broadcast.

5. Connect everything together. All audio sources go into the
mixer. Mixer main, stereo out needs to get into the mac. You will need
some adapter cables since the mac input is a mini phone jack.

6. Configure Nicecast to talk to your Via Streaming account, cue the
King Crimson...

7. Start a revolution!


--
http://artxfm.github.io/diy
