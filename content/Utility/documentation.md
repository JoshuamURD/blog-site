---
date-created: Thursday, July 13th 2023, 7:46:26 pm
---

# 1. Purpose of Vault

To curate knowledge from different forms of media. Primarily this will be literature, law and Youtube. The notes I will take here are intended to help me develop understanding and resonate with the things that I learn. Hopefully, links will be drawn between different ideas, and from it, original ideas may emerge. There is also an aspect of stoic philosophy behind the creation of this vault, it is to practice the art of meditating and observing the opinions or impressions as Epictetus might say, from my external. Many ideas from the books and Youtube videos I consume are excellent and have a lot to offer if they remain in my long-term knowledge. Knowledge without preservation is useless.

## 1.1. Why Have Information Stored?

These ideas and notes can hopefully be used to turn into projects. There will also eventually be project notes stored in here that are important to keep long term. For example, the first two projects I will be undertaking on this vault will be my family tree project and my philosophy blog project.

## 1.2. How to Add New Information

Most new information will be automatically taken care of as to where they go by the obsidian vault plugins which generate templates. Daily journalling and musings will be the first note that is generated upon opening the vault in Obisidian Mobile and on the Desktop. The notes for more "reference" notes I guess you could say, go into the inbox. For more information, see [[Utility/index.canvas|index]].

# 2. Theme

I am currently using the Minimal theme but have customised the font to be Gadugi for the note font and Arial for the system font (because it's simple and standard).

# 3. Plugins

- [ ] This needs updating

- **Dataview** - provides SQL-like querying of the YAML information in notes.
- **Commander** - allows for buttons and macro customisation.
- **Completr** - allows for fuzzy auto-completion of tags.
- **Linter** - provides automatic document formatting on saves.
- **Media extended** - allows for timestamped youtube videos.
- **Numbered headings** - creates a command to automatically number headings or remove that numbering as the case may be.
- **Omnisearch** - allows OCR searching of PDFs and images within the vault.
- **Pandoc** - allows for conversion to other filetypes.
- **PDF highlight extractor** - Allows the extraction of PDF highlights. This makes part of the literature-notes workflow.
- **Plugin update tracker** - a plugin to give notifications and changelog information on updates to plugins installed on the vault.
- **Style settings** - allows for free customisation of themes and fonts.
- **Table of contents** - generates a table of contents (not dynamically updated)
- **Text extractor** - a companion plugin to Omnisearch. Allows for the searching functionality.
- **Templater** - used for utilising templates and javascript within Obsidian.

# 4. Folder Structure

> [!example] New notes - first step
> - **Inbox** - If notes fall into any of the below, then you must create a note in that folder to generate Templater:
> 	- **quick-capture** - notes which are quick captures from my computer.
> 	- **literature-notes** - when you feel like you can be fucked, whether it comes from quick-capture or some other place, start developing notes for literature which contain your favourite quotes or keen insights or disagreements.
> 	- **youtube-videos** - If a particular youtube video is important enough it justifies taking notes on it, create a note in this folder. Be ready to provide the video link.
> 	- **university** - notes for university which have not been processed yet.

- **Archived vault notes** - Notes which are no longer relevant but aren't worth deleting.
- **Areas** - This will contain long-term topic folders - this can be seen as the zettlekasten permanent note. All sub-folders require a particularised index/MoC (Map of Content) The categories are as follows:
	- ***permanent-notes*** - ideas which have been processed and either are connected to other ideas or have open questions to possible new ideas within them.
	- ***blog-post*** - for potential posts to obsidian publish. See [[Areas/blog-post/index|index]] or more information.
	- ***literature-notes*** - for ideas and potentially any quotes from books I've read that are imperative i keep. See [[Areas/literature-notes/index|index]]
	- ***university*** - university notes. Please see [[Journal/Index]] for more information.
- **Attachments** - PDFs or other files of a non-markdown type which are connected to a note in the inbox which can at least identify its purpose.
- **Dataview reports** - the place that contains notes which query my notes using YAML information. Go to a folder's index to get a taxonomy of the tags to query.
- **Journal** - Quick capture from my phone and reflective journal. See [[Journal/Index|Index]] for more information.
- **Projects** - short-term or early day research projects or developed ideas. Once they progress to a significant object of my time, create a dedicated folder in "Areas" with a corresponding index.
	- ***budgeting*** - I am attempting to budget better now,
	- ***family-tree*** - creating a family tree and history which will contain voice recordings with Nan and biography of her and Pops life. This may later be expanded to include Mum's side of family history too.
	- **obsidian-publish** - notes for my obsidian publish project. I want to make a digital garden. However, I'd like to seek a free alternative if possible.
- **Templates** - contains templates to be used by Templater.
- **Utility** - Information about the vault, life administration such as budgets and other data collections.

# Naming convention
- Evidence - 
	- literary notes, youtube videos - Author Name - title-of-content
	- University lecture - class-name-lecture-[lecture number]
	- University reading - same as literature notes above.
- Ideas and concepts - lower-case with spaces.
- Indexes - all lower-case and hypens instead of spaces.

# 5. Methodology

## 5.1. Note-taking

- I take notes on [[tag-taxonomy|literature or video]] which automatically should create a templater note when creating a new file in their respective sub-folders in the [[Dashboard#Folder structure|inbox folder]].
	- My literature notes come from highlights of books from my tablet.
	- Articles from the web.
	- Videos content from various streaming services (primarily, Youtube).
- Everyday, I have thoughts or ideas or insights that need to be quickly captured. I also need to have the habit of keeping a stoic journal.[^1] These notes area automatically generated in the [[Journal/Journal index]] folder and are the note that opens on start-up on my computer and on my phone. These notes should ideally be processed daily to keep up the practice of having good [[fleeting notes]].
	- All fleeting notes must be kept as is, but not all of them will make it into the vault's permanent notes.
- each note in the vault must provide its own context.[^3]


## 5.2. Maintaining Vault

- As often as I can spare, I should come to the vault to develop [[fleeting notes]]. I shall have a menu of various dataview reports kept in the [[Dashboard#Folder structure|Dataview reports folder]] which will outline various outstanding tasks.
- When performing processing of a note, I shall ensure to separate ideas from their source and have them as their own note with no more than a paragraph. I need to ensure I only take notes I need to take.
- This set-up can be thought of as a 3d database.[^2] Ideas, concepts and evidence (in various forms of content) are separated out:
	- One idea (i.e principle, point or assertion), could have many different evidence notes (containing evidence to substantiate).
	- One piece of evidence could support many ideas and will always contain my rewording (only using verbatim quotation when incredibly necessary). Not all evidence deserves its own note and instead a footnote should be used with the [[#3. Plugins|footnotes plugin]] (don't try to create your own google).
	- Concept notes begin to form when ideas need to be grouped under one umbrella. Think of this like a map of content or asking a question and having the vault answer back by grouping several ideas to form a basic structure of an answer. An example could be "What is soundness of mind?" as a concept note, with several ideas linking different legal principles to determine this as their own idea notes (which link to evidence notes such as cases).
	- Think of indexes as a "map of maps" with metadata about a plethora of topics.
- **When creating a new folder -** Ensure to add to the [[#4. Folder Structure|folder structure]].

[^1]: [Stoics like Marcus Aurialies used to keep journals to keep careful track of their thoughts](https://whatisstoicism.com/stoicism-resources/how-to-keep-a-stoic-journal-7-days-of-example-entries/)
[^2]: Imagine graphite [molecule](https://asbury.com/resources/education/graphite-101/structural-description/), with each layer being a separate topic or set of ideas.