#### Admonition

A section of text that is separate from the main flow of text.

Admonitions are designed to that they can be quickly skipped over
if the user is not concerned with the topic.

In mkdocs-material admonitions are used to store text such as abstracts, 
note, info, tip, success, question, warning, failure, danger, bug, example and quote.

[mkdocs-material admonitions documentation](https://squidfunk.github.io/mkdocs-material/reference/admonitions/)

* Also known as: "call outs"

#### Automatic Build

Using an automatic process that generates HTML from the markdown files.

Automatic builds for mkdocs can be automatically executed whenever any part of the mkdocs.yml or the files
in the ```docs``` directory change.  On GitHub, a GitHub action can be configured to achieve this.

#### Code Highlighting

The process of rendering source code with visually distinct styles to enhance readability and comprehension.

Mkdocs material allows this feature to be enabled by changing the mkdocs.yml configuration file.

#### Concept Graph

A structured representation of concepts and their interrelationships, typically organized as nodes connected by edges.

Concept Graphs are used to create lesson plans and learning roadmaps that are customized to a students learning objectives.

#### Deep Linking

The ability to send a link to another person in a chat or e-mail that links
directly to a subsection of a document.

**Example:** You can send a link directly to a specific term in the [Glossary of Terms](#glossary)

#### Edit Icon

The ability to add an "Edit Icon" to the top of each page in a textbook.

Mkdocs material allows the Edit Icon to move the user directly to a form
where they can click the Edit icon to change text.  By doing a Save
a GitHub action can be triggered to update the HTML of the site.

This feature allows non-technical staff to change and preview changes without having to setup a local build process on their local computer or server.

#### Embedding

A numeric vector representation of text that encodes semantic meaning, enabling large language models and semantic search systems to compare and rank content based on conceptual similarity rather than just keyword matching.

**Example in an Intelligent Textbook:**
When a student highlights a concept, the intelligent textbook generates embeddings for that concept and searches its database of content for related topics that share similar embeddings. As a result, it can suggest complementary reading sections, practice questions, or simulations that align with the student’s current focus, thus enhancing personalized learning.

#### Favicon
A small icon associated with a webpage, displayed by web browsers in tabs, bookmarks, or address bars.

#### Formulas
Mathematical expressions that represent relationships between variables, constants, and functions.

#### GitHub Actions

A workflow automation service integrated into GitHub that executes predefined tasks in response to repository events.

#### Glossary

A controlled vocabulary that lists specialized terms and their definitions to ensure consistent understanding.

* Also known as: Glossary of Terms

#### Hyper-Personalization

The ability for a textbook to be customized to the needs of an individual learner.

Modern textbooks allow hyper-personalization to be done in real-time using chatbots and agents.

#### ISO Definition

A term definition is considered to be consistent with ISO metadata registry guideline ISO/IEC 11179 if it meets the following criteria:

1. Precise
2. Concise
3. Distinct
4. Non-circular
5. Unencumbered with business rules

#### Keyword Search

A retrieval method that matches documents against user-supplied words or phrases to identify relevant content.

See also: [semantic search](#semantic-search)

#### Learning Graph

A directed graph of concepts that reflects the order that concepts should be learned to master a new concept.

#### License

A legal instrument specifying permissions, conditions, and restrictions for using, modifying, or redistributing content or software.

mkdoc material allows you to place your license link on the footer of each page.

#### Link Checker

A tool that verifies the validity and accessibility of hyperlinks within a given set of documents or webpages.

#### Markdown

Markdown: A lightweight markup language with plain text formatting syntax designed to be easy to read and write. It is primarily used for creating formatted documents and web content, converting plain text to structured formats such as HTML or PDF through a rendering process.

Example:
Markdown syntax allows for the creation of structured content. For instance:

- To create a header: # Header 1 or ## Header 2
- To format text in bold: **bold text**
- To create a link: [Link text](https://example.com)
- To include an image: ![Alt text](image-url.png)

For example, to write a numbered list:

```markdown
1. Item 1
1. Item 2
1. Item 3
```

Markdown will be rendered as the following:

1. Item 1
1. Item 2
1. Item 3

Note that the item counter is automatically calculated.

#### Material

A popular theme for the [mkdocs](#mkdocs) build system.

The Material Theme currently has over [21K](https://github.com/squidfunk/mkdocs-material/) stars on GitHub.  This is more than 10x any of the other themes for mkdocs.

#### MicroSim

A small-scale, embedded interactive simulation designed to illustrate a concept interactively within educational content.

MicroSim are a core element of intelligent interactive textbooks.

See the [MicroSims for Education Website](https://dmccreary.github.io/microsims/)

#### MicroSite

A website that runs on a web server with no need for complex heavy APIs to expensive services such as a search engine.

#### Mkdocs

A documentation build system that leverages [Markdown](#markdown) syntax for generating textbooks and websites.

#### Navigation

In our textbooks we focus on left-side navigation systems since these
are the default navigation system and they are both intuitive and
familiar by our users.  Our users also tend to be using
screens that are wide landscape displays.  We discourage top navigation.

#### Quiz Management

Allow pages to contain self-assessments where the answers are hidden until the user
clicks on a "Show Answer" control.

Allow multiple-choice questions in a list to use the ordered-list labels A. B. C. D.

#### Search

Create a search function as part of the build process.

The mkdocs material theme generates a reverse index JSON file that is used to
list the pages that match search keywords.

Note that standard mkdocs search does not use embeddings and there is no
way to find similar documents.

#### Semantic Search

A retrieval method that interprets the contextual meaning of search terms to improve the relevance of search results.

Intelligent textbooks frequently create [embeddings](#embeddings) for words, phrases, paragraphs and pages so you can quickly find similar content.

#### Social Media Previews

Summaries automatically generated when a webpage link is shared on social platforms, often including a title, description, and image.

#### Table of Contents

A structured list of document sections and headings, enabling users to locate and navigate to specific topics easily.

#### Vis.js

A JavaScript library for rendering graph networks.

Vis.js is used to view and edit [learning graphs](#learning-graph) used by intelligent textbooks.

#### Website Analytics

The process of analyzing who is coming to your website, when they are visiting and what pages are being accessed.

The mkdocs material system provides a way to integrate free Google Analytics by adding four lines to your mkdocs.yml file.

See: [Tutorial on Google Analytics](./tutorial/google-analytics.md)#### p5.js

The JavaScript library most commonly used to render MicroSims.

Although there
are many other JavaScript libraries that can be used, because there
is a huge number of p5.js programs available for indexing by
web crawlers used by generative AI tools, p5.js dominates
the MicroSim ecosystems.

Other specialized libraries such as vis.js are used for tasks such
as simulating graph traversal algorithms.
