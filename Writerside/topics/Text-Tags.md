# Text Tags

## `<p>` (Paragraph)

This tag is used to define a paragraph of text.

<code-block lang="xml">
<![CDATA[
<p>Lorem ipsum makes me absolutely crazy. I can't stand it, but I have to use it.</p>
]]>
</code-block>

## `<h>` (Heading)

This tag is used to define a heading.

<code-block lang="xml">
<![CDATA[
<h level="1">Because every lesson needs a title</h>
]]>
</code-block>

<chapter title="Parameters" collapsible="true">
<deflist type="full">
<def title="level (required)">
The level of the heading. The value should be a number between 1 and 6, inclusive.
</def>
</deflist>
</chapter>

## Formatting Tags

<table>
    <tr>
        <th>Tag</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><code>&lt;strong&gt;</code></td>
        <td>Defines strong text</td>
    </tr>
    <tr>
        <td><code>&lt;em&gt;</code></td>
        <td>Defines emphasized text</td>
    </tr>
    <tr>
        <td><code>&lt;u&gt;</code></td>
        <td>Defines underlined text</td>
    </tr>
    <tr>
        <td><code>&lt;b&gt;</code></td>
        <td>Defines bold text</td>
    </tr>
    <tr>
        <td><code>&lt;sub&gt;</code></td>
        <td>Defines subscripted text</td>
    </tr>
    <tr>
        <td><code>&lt;sup&gt;</code></td>
        <td>Defines superscripted text</td>
    </tr>
    <tr>
        <td><code>&lt;del&gt;</code></td>
        <td>Defines deleted text</td>
    </tr>
    <tr>
        <td><code>&lt;ins&gt;</code></td>
        <td>Defines inserted text</td>
    </tr>
    <tr>
        <td><code>&lt;mark&gt;</code></td>
        <td>Defines marked/highlighted text</td>
    </tr>
</table>

## `<ul>` (Unordered List)

This tag is used to define an unordered list.

<code-block lang="xml">
<![CDATA[
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
]]>
</code-block>

<chapter title="Child tags" collapsible="true">
<deflist>
<def title="<li> (required)">
The list item.
</def>
</deflist>
</chapter>

## `<ol>` (Ordered List)

This tag is used to define an ordered list.

<code-block lang="xml">
<![CDATA[
<ol>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>
]]>
</code-block>

<chapter title="Child tags" collapsible="true">
<deflist>
<def title="<li> (required)">
The list item.
</def>
</deflist>
</chapter>

## `<def>` (Definition)

This tag is used to define a term and its definition.

<code-block lang="xml">
<![CDATA[
<def title="BLOC">
    BLOC is an XML-based markup language designed to describe educational content.
</def>
]]>
</code-block>

<chapter title="Parameters" collapsible="true">
<deflist type="full">
<def title="title (required)">
The term being defined.
</def>
</deflist>
</chapter>

## `<citation>`

This self-closing tag is used to define a citation.

<code-block lang="xml">
<![CDATA[
<citation title="The Chicago Manual of Style" author="University of Chicago Press" date="2017" url="https://www.chicagomanualofstyle.org/" />
]]>
</code-block>

<chapter title="Parameters" collapsible="true">
<deflist type="full">
<def title="title (required)">
The title of the source.
</def>
<def title="url (required)">
The URL of the source.
</def>
<def title="author">
The author of the source.
</def>
<def title="date">
The date of the source.
</def>
</deflist>
</chapter>

## `<note>`

This tag is used to define a note.

<code-block lang="xml">
<![CDATA[
<note>
    BLOC is open-source and free for commercial and non-commercial use.
</note>
]]>
</code-block>

## `<warning>`

This tag is used to define a warning.

<code-block lang="xml">
<![CDATA[
<warning>
    The video tag is not available if you have format set to "print".
</warning>
]]>
</code-block>