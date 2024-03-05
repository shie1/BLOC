# Visual & Interactive Tags

## `<img/>` (Image)

This tag is used to define an image. It is a self-closing tag.

<code-block lang="xml">
<![CDATA[
<img src="path/to/image.jpg" alt="Description of the image" />
]]>
</code-block>

<chapter title="Parameters" collapsible="true">
<deflist type="full">
<def title="src (required)">
The path to the image file.
</def>
<def title="alt (required)">
<ul>
<li>A description of the image.</li>
<li>It is used for accessibility purposes.</li>
</ul>
</def>
<def title="caption">
The caption for the image.
</def>
</deflist>
</chapter>

## `<video/>`

<warning>
This tag is not available if you have format set to "print".
</warning>

This tag is used to define a video. It is a self-closing tag.

<code-block lang="xml">
<![CDATA[
<video src="path/to/video.mp4" />
]]>
</code-block>

<chapter title="Parameters" collapsible="true">
<deflist type="full">
<def title="src (required)">
The path to the video file.
</def>
<def title="required">
<ul>
<li>Requires user to complete video for lesson completion.</li>
<li>It is a boolean attribute.</li>
</ul>
</def>
<def title="autoplay">
<ul>
<li>Specifies that the video will start playing as soon as it is ready.</li>
<li>It is a boolean attribute.</li>
</ul>
</def>
<def title="controls">
<ul>
<li>Specifies that the video controls should be displayed.</li>
<li>It is a boolean attribute.</li>
</ul>
</def>
<def title="loop">
<ul>
<li>Specifies that the video will start over again, every time it is finished.</li>
<li>It is a boolean attribute.</li>
</ul>
</def>
<def title="muted">
<ul>
<li>Specifies that the audio output of the video should be muted.</li>
<li>It is a boolean attribute.</li>
</ul>
</def>
<def title="poster">
The URL of an image to be shown while the video is downloading.
</def>
<def title="caption">
The caption for the video.
</def>
</deflist>
</chapter>

## `<audio/>`

<warning>
This tag is not available if you have format set to "print".
</warning>

This tag is used to define an audio file. It is a self-closing tag.

<code-block lang="xml">
<![CDATA[
<audio src="path/to/audio.mp3" />
]]>
</code-block>

<chapter title="Parameters" collapsible="true">
<deflist type="full">
<def title="src (required)">
The path to the audio file.
</def>
<def title="required">
<ul>
<li>Requires user to complete audio for lesson completion.</li>
<li>It is a boolean attribute.</li>
</ul>
</def>
<def title="autoplay">
<ul>
<li>Specifies that the audio will start playing as soon as it is ready.</li>
<li>It is a boolean attribute.</li>
</ul>
</def>
<def title="controls">
<ul>
<li>Specifies that the audio controls should be displayed.</li>
<li>It is a boolean attribute.</li>
</ul>
</def>
<def title="loop">
<ul>
<li>Specifies that the audio will start over again, every time it is finished.</li>
<li>It is a boolean attribute.</li>
</ul>
</def>
</deflist>
</chapter>