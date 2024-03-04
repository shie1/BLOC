# Core Structure Tags

These tags are used to define the structure of the lesson. They are the building blocks of a BLOC lesson.

## `<lesson>`

This tag is the root element of a BLOC lesson. It contains all the other tags that make up the lesson.

<code-block lang="xml">
<![CDATA[
<lesson>
    <title>Because every lesson needs a title</title>
    <author>Optional Author</author>
    <date>2020-01-01</date>
    <content>
        <!-- Sections go here -->
    </content>
</lesson>
]]>
</code-block>

<chapter title="Parameters" collapsible="true">
<deflist type="full">
<def title="lang (optional)">
The language of the lesson. The value should be an ISO 639-1 language code. (e.g., "en" for English, "es" for Spanish, etc.)
</def>
</deflist>
</chapter>

<chapter title="Child tags" collapsible="true">
<deflist>
<def title="<title> (required)">
The title of the lesson.
</def>
<def title="<date> (required)">
The date the lesson was last updated.
</def>
<def title="<author>">
The author of the lesson.
</def>
<def title="<content> (required)">
The content of the lesson.
</def>
</deflist>
</chapter>

## `<content>`

This tag contains all the content of the lesson. It can contain one or more `<section>` tags.

## `<section>`

Defines a major section or subdivision within a lesson.

<code-block lang="xml">
<![CDATA[
<section>
    <title>Because every section needs a title</title>
    <p>Lorem ipsum makes me absolutely crazy. I can't stand it, but I have to use it.</p>
</section>
]]>
</code-block>

<chapter title="Parameters" collapsible="true">
<deflist type="full">
<def title="id (optional)">
<ul>
<li>A unique identifier for the section.</li>
<li>This can be used to create links to the section from other parts of the lesson.</li>
<li>If not provided, the section will be assigned an automatically generated ID from the title.</li>
</ul>
</def>
</deflist>
</chapter>

## `<title>`

The title of the lesson or section. Every lesson and section requires having a title.