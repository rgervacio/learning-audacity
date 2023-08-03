# Record audio

Recording audio involves recording voiceover, vocals, or instrumentals for your project using the currently selected input device.

!!! note

    Before recording, ensure that you have configured your preferred <a href="/learning-audacity/playing-and-recording-a-project/change-recording-settings/">recording</a> and <a href="/learning-audacity/playing-and-recording-a-project/change-playback-settings">playback</a> settings. After recording, if the recorded audio isn’t centered at the 0.0 line on the Vertical scale, <a href="/learning-audacity/applying-common-audio-effects/change-overall-volume-level/#normalize-audio">normalize the track</a> to remove the DC offset before editing and applying effects. DC offset can result in clipping, distortion, and popping sounds.
    
    <img src="/learning-audacity/assets/images/Vertical Scale - DC offset.png"  />

!!! tip

    After clicking record, wait about 10 seconds before speaking, singing, or playing into the microphone. The silence serves as a buffer and a way of getting room tone, which you can use as a baseline for <a href="/learning-audacity/editing-a-project/remove-background-noise/">noise reduction</a>. You can delete this part of the track after recording and removing background noise.

<br/>

## Record audio in a blank project

To record audio in a blank project:

1. On the Transport toolbar, click **Record**.

    <img src="/learning-audacity/assets/images/Transport Toolbar - Record.png" />

    !!! solid-keyboard "Shortcut"

        Press <kbd>R</kbd> .

2. Speak, sing, or play the instrument into the microphone.

3. Once you finish recording, click **Stop**.

    <img src="/learning-audacity/assets/images/Transport Toolbar - Stop.png" />

<br/>

## Record audio in the same track

Recording audio in the same track is useful for recordings that don’t require extensive editing or moving, such as a speech or presentation monologue.

To record audio in the same track:

1. Press and hold <kbd>Shift</kbd> .

1. On the Transport toolbar, click **Record**.

    <img src="/learning-audacity/assets/images/Transport Toolbar - Record.png" />

    !!! solid-keyboard "Shortcut"    
    
        Press <kbd>Shift</kbd> + <kbd>R</kbd> .

2. Speak, sing, or play the instrument into the microphone.

3. Once you finish recording, click **Stop**.

    <img src="/learning-audacity/assets/images/Transport Toolbar - Stop.png" />

<br/>

## Record audio in a new track

Recording audio in a new track is useful for recordings that require editing or moving different sections individually, such as a podcast or multitrack mix.

To record audio in a new track:

1. Choose where you want to start recording on the Timeline:

      - To start recording at the beginning of the Timeline, on the Transport toolbar, click **Skip to Start**.

        <img src="/learning-audacity/assets/images/Transport Toolbar - Skip to start.png" /><br/><br/>

      - To start recording at the end of the Timeline, on the Transport toolbar, click **Skip to End**.

        <img src="/learning-audacity/assets/images/Transport Toolbar - Skip to end.png" /><br/><br/>

      - To record elsewhere on the Timeline, click the part of the current track where you want to begin recording the new track.<br/>

2. Create a new track:

    === "If **Record on a new track** is enabled"

        - A new track will be created automatically once you begin recording.
      
    === "If **Record on a new track** is disabled"

        - Go to **Tracks** \> **Add New** \> **Mono Track** or **Stereo Track**.

3. On the Transport toolbar, click **Record**.

    <img src="/learning-audacity/assets/images/Transport Toolbar - Record.png" />

4. Speak, sing, or play the instrument into the microphone.

5. Once you finish recording, click **Stop**.

    <img src="/learning-audacity/assets/images/Transport Toolbar - Stop.png" />

<br/>

## Record two tracks simultaneously

Recording two tracks simultaneously is useful for recording audio from two sources, such as separate mics for different participants in an interview or vocals and instrumentals in a song.

To do this in Audacity, you must record the two tracks as a single stereo track and split them into two separate mono tracks. This method allows you to apply effects and adjust each source’s pan and gain separately.

!!! note

    Recording audio from multiple sources requires using an audio interface or mixer with enough input jacks for the microphones.

<br/>First, record the two tracks as a single stereo track:

1. On the Audio setup toolbar, click **Audio Setup** \> **Recording Channels** \> **2 (Stereo) Recording Channels**.

    <img src="/learning-audacity/assets/images/Audio Setup Toolbar - Recording Channels - Stereo.png"  />

2. On the Transport toolbar, click **Record**.

    <img src="/learning-audacity/assets/images/Transport Toolbar - Record.png" />

3. Speak, sing, or play the instrument into the microphones.

4. Once you finish recording, click **Stop**.

    <img src="/learning-audacity/assets/images/Transport Toolbar - Stop.png" />


<br/>Second, split the stereo track into two separate mono tracks:

1. On the Track control panel, click the **Track dropdown menu**.

    <img src="/learning-audacity/assets/images/Track Control Panel - Name - Stereo.png" />

2. Select **Split Stereo Track**.

<br/>Third, adjust the tracks’ pan and gain:

1. On the first track’s Track control panel, drag the **Pan slider** to the center so that the sound coming out of the left and right headphones or speakers is balanced.

    <img src="/learning-audacity/assets/images/Track Control Panel - Pan Slider.png" />

2. Drag the **Gain slider** to your preferred volume level:

    <img src="/learning-audacity/assets/images/Track Control Panel - Gain Slider.png" />

      - To increase the gain, drag the slider to the right.

      - To decrease the gain, drag the slider to the left.

3. Repeat steps 1 and 2 to adjust the second track’s pan and gain.

<br/>