# Monitor audio

Monitoring audio involves checking the recording and playback levels to ensure that the audio isn’t too loud or too quiet. It also involves configuring your recording settings accordingly to save time from not having to rerecord audio due to clipping or distortion.

!!! tip 

    Ideally, you should do a quick test recording and monitor the audio before actually recording to ensure that there are no problems with the volume.

<br/>

## Monitor recording level

Monitoring recording level using the **Recording meter toolbar** involves checking the input signal volume and adjusting the recording level. This is useful for seeing whether you need to increase or decrease the recording level before recording.

To monitor recording level:

1. On the Recording meter toolbar, click the **Microphone button** \> **Start Monitoring**.

    <img src="/learning-audacity/assets/images/Recording Meter Toolbar - Start Monitoring.png"  />

2. Speak or play the instrument into the microphone at the same volume level you plan on speaking or playing when recording.

3. Watch the Recording meter while speaking or playing and keep track of the input signal’s current peak level, recent peak level, and maximum peak level.

    <img src="/learning-audacity/assets/images/Recording Meter Toolbar - Recording Level - Peak Levels.png" /><br/>

    !!! note 
    
        Ideally, the input signal should be somewhere **between -12 dB and -6 dB**. To prevent creating potential clipping or distortion, don’t let the input signal exceed -3 dB or reach the red area in the far right of the meter. Clipping occurs when the input signal exceeds 0 dB.  

        <img src="/learning-audacity/assets/images/Recording Meter Toolbar - Monitor Recording Level - Ideal and Clipping.png"  />

    !!! tip
    
        To expand the Recording meter toolbar and see a larger scale: <br/>&nbsp;&nbsp;&nbsp;&nbsp;1. Drag the **toolbar** **grabber** and move the toolbar into its own free-floating panel.  
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="/learning-audacity/assets/images/Recording Meter Toolbar - Grabber.png"  />  <br/>&nbsp;&nbsp;&nbsp;&nbsp;2. Drag the **bottom-left corner** vertically or horizontally.  
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="/learning-audacity/assets/images/Recording Meter Toolbar - Resize.png"  /><br/>  
        To reset the toolbar to its original position in the project window, go to **View** \> **Toolbars** \> **Reset Toolbars**.

4. If the input signal is too loud or too quiet, drag the **slider** to your preferred recording level or adjust the input controls on the microphone and/or other recording device.

    <img src="/learning-audacity/assets/images/Recording Meter Toolbar - Recording Level Slider.png"  />

    !!! note

        If the input signal is too quiet, you can always increase the volume by <a href="/learning-audacity/editing-a-project/adjust-track-gain/">increasing the gain</a> or <a href="/learning-audacity/applying-common-audio-effects/change-overall-volume-level/#amplify-audio">amplifying the audio</a>. However, if the input signal is too loud, you’ll be unable to fix the audio clipping or distortion after recording.

5. Repeat steps 2 to 4 until the input signal volume isn’t too loud or too quiet.

<br/>

To stop monitoring recording level:

- On the Recording meter toolbar, click the **Microphone button** \> **Stop Monitoring**.

    <img src="/learning-audacity/assets/images/Recording Meter Toolbar - Stop Monitoring.png"  />

<br/>

## Monitor playback level

Monitoring playback level using the **Playback meter toolbar** involves checking the output signal volume and adjusting the playback level. This is useful for seeing whether you need to increase or decrease the audio volume after recording.

To monitor playback level:

1. On the Tools toolbar, click the **Selection tool**.

    <img src="/learning-audacity/assets/images/Tools Toolbar - Selection Tool.png"  />

2. Select the section of audio that you want to monitor.

3. On the Transport toolbar, click **Play**.

    <img src="/learning-audacity/assets/images/Transport Toolbar - Play.png" />

4. Watch the Playback meter and keep track of the output signal’s
current peak level, recent peak level, and maximum peak level.

    <img src="/learning-audacity/assets/images/Playback Meter Toolbar - Playback Level - Peak Levels.png" style="width:3.03087in;height:1.9685in" />

    !!! note
        
        Ideally, the output signal should be somewhere **between -12 dB and -6 dB**. To prevent hearing potential clipping or distortion, don’t let the output signal exceed -3 dB or reach the red area in the far right of the meter.  
        
        <img src="/learning-audacity/assets/images/Playback Meter Toolbar - Monitor Playback Level - Ideal and Clipping.png" style="width:3.293in;height:0.65652in" />  

    !!! tip 
     
        To expand the Playback meter toolbar and see a larger scale:  <br/>&nbsp;&nbsp;&nbsp;&nbsp;1. Drag the **toolbar** **grabber** and move the toolbar into its own free-floating panel.<br/>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="/learning-audacity/assets/images/Playback Meter Toolbar - Grabber.png" />  <br/>&nbsp;&nbsp;&nbsp;&nbsp;2. Drag the **bottom-left corner** vertically or horizontally. <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="/learning-audacity/assets/images/Playback Meter Toolbar - Resize.png"  />  <br/><br/>To reset the toolbar to its original position in the project window, go to **View** \> **Toolbars** \> **Reset Toolbars**.

1. If the output signal is too loud or too quiet, change the audio volume by <a href="/learning-audacity/editing-a-project/adjust-track-gain/">adjusting the gain</a> or using the <a href="/learning-audacity/applying-common-audio-effects/change-overall-volume-level/#amplify-audio">Amplify</a>, <a href="/learning-audacity/applying-common-audio-effects/change-overall-volume-level/#normalize-audio">Normalize</a>, or <a href="/learning-audacity/applying-common-audio-effects/change-overall-volume-level/#compress-audio">Compressor</a> effect.

    !!! note

        Adjusting the Playback level slider only changes the project’s playback volume in Audacity. It won’t change any actual waveform data or affect an exported project’s volume level.

2. Repeat steps 3 to 5 until the output signal volume isn’t too loud or too quiet.

<br/>