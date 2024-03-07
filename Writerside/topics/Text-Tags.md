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

## Inline Formatting Tags

These tags are used to define inline formatting.
<code-block collapsed-title="Inline formatting examples" collapsible="true" lang="xml">
<![CDATA[
<p>
    <strong>Strong text</strong> is important.
    <em>Emphasized text</em> is also important.
    <u>Underlined text</u> is not as important.
    <b>Bold text</b> is also important.
    <sub>Subscripted text</sub> is not as important.
    <sup>Superscripted text</sup> is also important.
    <del>Deleted text</del> is not as important.
    <ins>Inserted text</ins> is also important.
    <mark>Marked/highlighted text</mark> is also important.
</p>
]]>
</code-block>

<table>
    <tr>
        <th>Tag</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><code>&lt;strong&gt;</code></td>
        <td>Strong text</td>
    </tr>
    <tr>
        <td><code>&lt;em&gt;</code></td>
        <td>Emphasized text</td>
    </tr>
    <tr>
        <td><code>&lt;u&gt;</code></td>
        <td>Underlined text</td>
    </tr>
    <tr>
        <td><code>&lt;b&gt;</code></td>
        <td>Bold text</td>
    </tr>
    <tr>
        <td><code>&lt;sub&gt;</code></td>
        <td>Subscripted text</td>
    </tr>
    <tr>
        <td><code>&lt;sup&gt;</code></td>
        <td>Superscripted text</td>
    </tr>
    <tr>
        <td><code>&lt;del&gt;</code></td>
        <td>Deleted text</td>
    </tr>
    <tr>
        <td><code>&lt;ins&gt;</code></td>
        <td>Inserted text</td>
    </tr>
    <tr>
        <td><code>&lt;mark&gt;</code></td>
        <td>Marked/highlighted text</td>
    </tr>
    <tr>
        <td><code>&lt;br /&gt;</code></td>
        <td>Line break</td>
    </tr>
    <tr>
        <td><code>&lt;code&gt;</code></td>
        <td><p>Inline code</p>Use <code>&lt;code-block&gt;</code> for multi-line, language-specific code snippets</td>
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
You can also use `<definiton>` as an alias for `<def>`.

<tabs>
<tab title="def">
<code-block lang="xml">
<![CDATA[
<def title="BLOC">
    BLOC is an XML-based markup language designed to describe educational content.
</def>
]]>
</code-block>
</tab>
<tab title="definition">
<code-block lang="xml">
<![CDATA[
<definition title="BLOC">
    BLOC is an XML-based markup language designed to describe educational content.
</definition>
]]>
</code-block>
</tab>
</tabs>

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