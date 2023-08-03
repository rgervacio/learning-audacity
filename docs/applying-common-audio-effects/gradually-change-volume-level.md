# Gradually change volume level

Gradually changing volume level involves using the **Envelope tool** or **Fade in**, **Fade out**, **Crossfade tracks**, or **Crossfade clips effects**. All five of these methods can gradually increase or decrease volume level. However, the type of method(s) that you should use will depend on how you want the audio to sound.

<table width="100%">
  <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
  </colgroup>
  <thead>
    <tr class="header">
      <th style="text-align: center;"><strong>If you want to…</strong></th>
      <th style="text-align: center;"><strong>… then… </strong></th>
    </tr>
  </thead>
  <tbody>
    <tr class="odd">
      <td>
        <ul>
          <li>
            <p>Gradually increase the volume level of specific sections of audio</p>
          </li>
        </ul>
      </td>
      <td><a href="#fade-in-audio">Fade in audio</a></td>
    </tr>
    <tr class="even">
      <td>
        <ul>
          <li>
            <p>Gradually decrease the volume level of specific sections of audio</p></li>
          </ul>
      </td>
      <td><a href="#fade-out-audio">Fade out audio</a></td>
    </tr>
    <tr class="odd">
      <td>
        <ul>
          <li>
            <p>Create seamless transitions between tracks</p>
          </li>
        </ul>
      </td>
      <td><a href="#crossfade-tracks">Crossfade tracks</a></td>
    </tr>
    <tr class="even">
      <td>
        <ul>
          <li>
            <p>Create seamless transitions between clips</p>
          </li>
        </ul>
      </td>
      <td><a href="#crossfade-clips">Crossfade clips</a></td>
    </tr>
    <tr class="odd">
      <td>
        <ul>
          <li>
            <p>Smoothen the volume level of specific sections of audio</p>
          </li>
        </ul>
      </td>
      <td><a href="#adjust-volume-changes">Adjust volume changes</a></td>
    </tr>
  </tbody>
</table>

!!! note

    Audacity is primarily a destructive editor. Destructive editing means that changes applied to the audio permanently change its waveform. For example, if you apply an effect, save your progress, and close the project, you’ll be unable to restore the version of the project that contained the original audio the next time you open it in Audacity. For this reason, you should have two copies of your project: one copy to edit and another to keep as a master copy with unaltered audio in case you want to undo any unwanted permanent changes. <br/><br/>
    Newer versions of Audacity (3.2.0 and newer) also have non-destructive plug-ins (“realtime effects”) that don’t change the waveform and are reversible. However, this guide currently doesn’t cover how to use these plug-ins.

<br/>

### Fade in audio

Fading in audio using the **Fade in** **effect** allows you to gradually increase the volume of specific sections of audio. This is useful for making the introductions of songs and podcast segments sound more natural and less abrupt.


To fade in audio:

1. On the Tools toolbar, click the **Selection tool**.

    <img src="/learning-audacity/assets/images/Tools Toolbar - Selection Tool.png" />

1. Select the section of audio that you want to fade in.

1. Go to **Effect** \> **Fade In**.

    !!! tip

        If the selected audio doesn’t completely fade in, delete the tail-end of silent audio in the selection before applying the effect.

    !!! tip

        To control and <a href="#adjust-volume-changes">adjust the fade effect further</a>, use the **Envelope tool** to smoothen the volume.

<br/>

### Fade out audio

Fading out audio using the **Fade out** **effect** allows you to gradually decrease the volume of specific sections of audio. This is useful for making the endings of songs and podcast segments sound more natural and less abrupt.

To fade out audio:

1. On the Tools toolbar, click the **Selection tool**.

    <img src="/learning-audacity/assets/images/Tools Toolbar - Selection Tool.png" />

1. Select the section of audio that you want to fade out.

1. Go to **Effect** \> **Fade Out**.

    !!! tip

        If the selected audio doesn’t completely fade out, delete the tail-end of silent audio in the selection before applying the effect.

    !!! tip

        To control and <a href="#adjust-volume-changes">adjust the fade effect further</a>, use the **Envelope tool** to smoothen the volume.

<br/>

### Crossfade tracks

Crossfading tracks using the **Crossfade tracks** **effect** allows you to create a seamless transition between one track and the next without adding any jarring audio changes. This is useful for merging different songs in a song compilation and making podcast segment introductions and endings sound more natural and less abrupt.

To crossfade tracks:

1. On the Tools toolbar, click the **Selection tool**.

    <img src="/learning-audacity/assets/images/Tools Toolbar - Selection Tool.png" />

2. Trim any unwanted sections of audio.

3. Move the tracks’ clips to the desired audio positions.

4. Move the clip that’s inside the second track and overlap a portion of its intro end with the outro end of the clip that’s inside the first track.

    <img src="/learning-audacity/assets/images/Crossfade Tracks - Labelled.png" />

    !!! note

        Overlapping audio will play at the same time.

5. Select the overlapping sections of audio in both of the tracks.

    !!! note

        The crossfade length depends on the selection length. The beginning of the selection is where the crossfade will begin, and the end of the selection is where the crossfade will end.

6. Go to **Effect** \> **Crossfade Tracks**.

7. In the dialog box, configure your preferred crossfade settings.

    <img src="/learning-audacity/assets/images/Crossfade Tracks dialog box.png" />

    ??? solid-gear "Configuration"

        <h4>Fade type</h4> 
        
        This setting adjusts how an audio selection fades in or fades out:

        - **Constant Gain** fades out audio in the first track and fades in audio in the second track using a linear fade. It prevents the crossfade from clipping (as long as the original audio doesn’t clip) but may drop the overall volume slightly as the audio fades.

        - **Constant Power 1** works like Constant Gain but prevents the overall volume from dropping and may boost the peak volume level as the audio fades.

        - **Constant Power 2** works like Constant Power 1 but fades audio quicker and may make the crossfade sound more abrupt.

        - **Custom Curve** enables the Custom curve option, which allows you to adjust the fade manually.
  
        <br/>
        <h4>Custom curve</h4>
  
        This setting adjusts the fade’s curvature and allows for more control of the fade effect. To enable this option, select **Custom Curve** in the Fade Type dropdown menu.
  
        Change the custom curve using the **value box** or **slider**:

        - To make both tracks more prominent during the crossfade (fade out the first track and fade in the second track less gradually), drag the slider to the right.

        - To make both tracks less prominent during the crossfade (fade out the first track and fade in the second track more gradually), drag the slider to the left.
        
        <br/>
        <h4>Fade direction</h4> 
        
        This setting controls whether the intro or outro end of a track fades in or fades out:

         - **Automatic** automatically detects whether to fade in or fade out a track. It generally produces the correct result.

         - **Alternating Out / In** fades out the first track and fades in the second track. If there are any subsequent tracks selected, the fade direction will alternate between fading out and fading in the tracks.

         - **Alternating In / Out** fades in the first track and fades out the second track. If there are any subsequent tracks selected, the fade direction will alternate between fading in and fading out the tracks.

    !!! note
        
        You may need to configure the settings through trial and error until you get your preferred result. To preview the audio before applying the settings, click **Preview**.

    !!! tip 
        
        To save the crossfade settings as a preset for future use, click **Presets & settings** \> **Save Preset**.

    !!! tip

        To control and <a href="#adjust-volume-changes">adjust the fade effect further</a>, use the **Envelope tool** to smoothen the volume.

8. Click **Apply**.

<br/>

### Crossfade clips

Crossfading clips using the **Crossfade clips effect** allows you to create a seamless transition between one clip and the next. This is useful for joining different songs smoothly without adding any jarring audio changes or silence and making introductions and endings of podcast segments sound more natural and less abrupt.

To crossfade clips:

1. On the Tools toolbar, click the **Selection tool**.

    <img src="/learning-audacity/assets/images/Tools Toolbar - Selection Tool.png" />

1. Trim any unwanted sections of audio.

1. Move the clips so that they are next to each other at the desired audio positions.

1. Select a section of audio that contains the first clip’s outro end and the second clip’s intro end.

    <img src="/learning-audacity/assets/images/Crossfade Clips - Labelled.png"  />

    !!! note

        The crossfade length depends on the selection length. The beginning of the selection is where the crossfade will begin, and the end of the selection is where the crossfade will end.

    !!! tip

        To control and <a href="#adjust-volume-changes">adjust the fade effect further</a>, use the **Envelope tool** to smoothen the volume.

2. Go to **Effect** \> **Crossfade** **Clips**.

<br/>

### Adjust volume changes

Adjusting volume changes using the **Envelope tool** allows you to edit a track’s waveform and smoothen the volume levels of specific sections of audio. This is useful for blending different audio elements together, such as adjusting voiceover and background music volume at certain points in a track.

!!! note

    The Envelope tool can’t fade audio completely. If you need to completely fade audio, use the <a href="#fade-in-audio">Fade in</a> or <a href="#fade-out-audio">Fade out</a> effect instead.

<br/>

To adjust volume changes:

1. On the Tools toolbar, click the **Envelope tool**.

    <img src="/learning-audacity/assets/images/Tools Toolbar - Envelope Tool.png" />

2. Click and place a **control point** on the part of the track where you want to adjust the volume level:

    <img src="/learning-audacity/assets/images/Envelope Tool - Control point.png"  />

      - To move a control point left or right, drag it along the track.

      - To delete a control point, drag it off the track.

3. Drag the outer or inner **control point** up or down to change the volume level:

    <img src="/learning-audacity/assets/images/Envelope Tool - Control point - Inner and outer.png" />

      - To increase the volume level, drag the control point up.

      - To decrease the volume level, drag the control point down.

    !!! tip

        Dragging an outer control point prevents you from dragging it outside the track’s original volume envelope and distorting the audio. Dragging an inner control point has the same effect as dragging an outer control point and also allows you to amplify quiet audio beyond the track’s original volume envelope.  

4. Repeat steps 2 and 3 to adjust the volume levels of other sections of audio.

<br/>