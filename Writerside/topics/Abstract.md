# Abstract

BLOC (Building Lessons with Organized Content) is an XML-based markup language purpose-built for describing educational
materials. Its intuitive design emphasizes simplicity, modularity, and extensibility, making it ideal for various
instructional content formats.
<note>
    BLOC is open-source and free for commercial and non-commercial use.
</note>

<code-block collapsed-title="Example BLOC Lesson" lang="xml" collapsible="true">
<![CDATA[
<?xml version="1.0" encoding="utf-8" ?>
<?bloc version="1.0" format="print" ?>
<lesson>
    <title>An Intoduction to BLOC</title>
    <author>John Doe</author>
    <date>2020-01-01</date>
    <content>
        <section>
            <title>What is BLOC?</title>
            <definition title="BLOC">
                BLOC is an XML-based markup language designed to describe educational content.
            </definition>
        </section>
        <section>
            <title>Key Features</title>
            <ul>
                <li>Descriptive</li>
                <li>Simple</li>
                <li>Modular</li>
                <li>Extensible</li>
            </ul>
        </section>
        <section>
            <title>Uses</title>
            <p>BLOC is an ideal tool for describing a wide range of educational materials, including:</p>
            <ul>
                <li>Online courses</li>
                <li>Printed textbooks</li>
                <li>Interactive tutorials</li>
                <li>Quizzes and assessments</li>
            </ul>
        </section>
    </content>
</lesson>
]]>
</code-block>

BLOC has been designed to address the challenges of creating and managing educational content, such as:

<deflist type="full">
<def title="Serving the same content in different formats (e.g., web pages, eBooks, PDFs)">
BLOC's XML foundation allows for easy transformation and styling, providing a single source for diverse outputs.
</def>
<def title="Reusing content across different courses or materials">
BLOC's modular structure makes it easy to repurpose lessons, sections, or individual content elements.
</def>
<def title="Storing interactive content (e.g., quizzes, assessments)">
BLOC contains tags for embedding interactive content.
</def>
</deflist>

## Why use BLOC?
BLOC streamlines the creation and management of high-quality educational content, empowering educators to focus on what matters most – teaching.

BLOC addresses common challenges like:
- Disorganized content
- Inefficient authoring processes
- Limited flexibility and adaptability
- Difficulty incorporating interactive elements
- Accessibility barriers