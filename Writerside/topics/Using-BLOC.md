# Writing with BLOC


Here's a guide to get you started, along with some additional considerations for future development.

<note>
<p>We are planning to develop a visual editor for BLOC.</p>
Currently, there is no way to visually create BLOC lessons. You will need to write the XML manually.
</note>

## Understanding the Fundamentals

XML: Review the basics of XML (tags, attributes, syntax) if you're unfamiliar with it. There are great online resources to help you get familiar with this.
Core BLOC Tags: Learn the essential tags for structuring and formatting BLOC lessons (`<lesson>`, `<content>`, `<section>`, `<title>`, text tags, list tags, etc.). Refer to the abstract and example lesson provided in previous responses.

## Choose a Text Editor

Any Plain Text Editor: You can write BLOC in a simple text editor (Notepad, TextEdit, etc.), but you won't get the benefits of an XML-aware editor. A specialized editor like (VS Code, Atom, Oxygen XML) will provide better support:
- Syntax highlighting for easier reading
- Potential XSD validation based on the schema we developed

## Create Your First Lesson

- **Structure**: Start with a basic lesson structure, including title, author, date, and a few section elements.
- **Content**: Within sections, add paragraphs (`<p>`), headings (`<h>`), lists (`<ul>`, `<ol>`), etc.
- **Experiment**: Try using tags like `<strong>`, `<em>`, `<def>`, `<img>`, and others to include formatting and enriching elements.

## Validate Your Lesson

- **Schema**: Ensure that your lesson is valid against the BLOC schema. This will help you catch any errors or inconsistencies in your lesson.
- **Tools**: Use an XML-aware editor to validate your lesson against the schema. This will help you identify and correct any issues.