# Pan audio

Panning audio using the **Pan slider** allows you to control how audio is distributed across the left and right channels (or left and right speakers or headphones) of a stereo field.
<br/>

## Pan a track

Panning a track allows you to control how loud a track plays in the left and right speakers or headphones. This is useful for balancing a track’s audio distribution and controlling different tracks that play at different positions of the stereo field.

To pan a track:

- On the Track control panel, drag the **Pan slider**:

    <img src="/learning-audacity/assets/images/Track Control Panel - Pan Slider.png" />

    - To pan audio to the right, drag the slider to the right.

    - To pan audio to the left, drag the slider to the left.

    !!! note

        Panning audio won’t change any actual waveform data until you <a href="/learning-audacity/editing-a-project/mix-tracks/">mix the track</a> or <a href="/learning-audacity/managing-a-project/export-a-project/#export-an-entire-project">export the project</a>.

    !!! tip

        To pan the track more precisely, press and hold <kbd>Shift</kbd> , and then drag or double-click the **Pan slider** and enter a specific value in the dialog box.

    !!! tip

        To <a href="/learning-audacity/playing-and-recording-a-project/monitor-audio/#monitor-playback-level">monitor the panning audio</a>, look at the **Playback meter** and keep track of the playback levels in the left and right channels. To better hear the panning effect, <a href="/learning-audacity/editing-a-project/mute-and-solo-a-track/#solo-a-track">solo the track</a> or <a href="/learning-audacity/editing-a-project/mute-and-solo-a-track/#mute-a-track">mute all of the other tracks</a>.

<br/>

## Pan audio left and right

Panning audio left and right allows you to move audio from one speaker or headphone to the other. This is useful for creating an immersive and seamless transition when audio changes position in the stereo field.

To pan audio left and right:

1. Create two separate mono tracks that contain the same audio:

    === "If current track is a stereo track"

        1. Select the track.
      
        2. Go to **Tracks** \> **Mix** \> **Mix Stereo Down to Mono**.

        3. Go to **Edit** \> **Duplicate**. 

    === "If current track is a mono track"

        4.  Select the track.

        5.  Go to **Edit** \> **Duplicate**.


2. On the first track’s Track control panel, drag the **Pan slider**:

      - To pan audio from left to right, drag the slider all the way to the left.

      - To pan audio from right to left, drag the slider all the way to the right.<br/>

3. On the second track’s Track control panel, drag the **Pan slider**:

      - To pan audio from left to right, drag the slider all the way to the right.

      - To pan audio from right to left, drag the slider all the way to the left.
  
4. On the Tools toolbar, click the **Envelope tool**.

      <img src="/learning-audacity/assets/images/Tools Toolbar - Envelope Tool.png" />

5. Adjust and smoothen the panning effect.

      <img src="/learning-audacity/assets/images/Pan effect from left to right.png" />
    
    _An example of a panning effect in which audio moves from the left headphone or speaker to the right headphone or speaker._<br/>

    !!! note

        For more information on how to use the Envelope tool to smoothen volume level, see <a href="/learning-audacity/applying-common-audio-effects/gradually-change-volume-level/#adjust-volume-changes">Adjust volume changes</a>.

6. Convert both of the mono tracks to a single stereo track (optional):

      1.  Select both tracks.

      2.  On one of the tracks’ Track control panels, click the **Track dropdown menu**.
   
        <img src="/learning-audacity/assets/images/Track Control Panel - Pan track name.png" />

      3.  Select **Make Stereo Track**.

<br/>
