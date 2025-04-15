# Documentation Project

This is a documentation project organized using the PARA method, with Zettelkasten principles for individual notes and MOCs (Maps of Content) as navigation hubs.

## Organization Structure

### 1. PARA Method (Projects, Areas, Resources, Archives)

This knowledge management system provides four top-level categories:

- **Projects/**: Active documentation work with deadlines
- **Areas/**: Ongoing documentation topics
- **Resources/**: Reference materials and topics of interest
- **Archives/**: Inactive projects

### 2. Zettelkasten Method (Atomic Notes)

This approach focuses on creating small, atomic notes:

- Each note contains one discrete concept or piece of information
- Notes are linked together to form a network of ideas in the MOCs
- Uses a flat structure rather than deep hierarchies
- Relies on links and tags rather than folders

### 3. MOC (Maps of Content) Approach

This acts as a middle ground:

- Create "hub" notes that serve as tables of contents for specific domains
- These hub notes link to all relevant content in that area
- Notes can be referenced in multiple MOCs without duplication
- The actual content lives in its own notes, linked from multiple places

## Further Details

### 1. Folder Structure

- Projects/
  - Project 1/
    - notes/
      - MOC
      - MOC N
      - note 1
      - note N
    - resources/
      - folder 1/
        - MOC
        - items
      - folder N/
    - README.md
  - Project N/
- Areas/
  - MOC
  - MOC N
  - note 1
  - note N
- Resources/
  - folder 1/
    - MOC
    - items
  - folder N/
- Archives/
  - Project 1/

### 2. Note Details

- Notes are created as atomic notes
- The filename follows the format: YYYYMMDDHHmm-[Title].md
  - The title should be a sentence that summarizes the content
- The content should be a small unit of information written in markdown
- The note should have frontmatter

#### Frontmatter Format

```yaml
---
title: "Note Title"
description: "Brief summary of the note's content"
tags: [tag1, tag2, tag3]
medium: [url, book, paper, thought, conversation, meeting]
---
```

### 3. MOC Details

- MOCs are created as a table of contents for a specific domain
- MOCs can have sections grouped by subjects or the sections can be split into new MOCs
- The filename follows the format: 000-[Title]-MOC.md
- MOCs should not use a frontmatter

### 4. Linking

- Links should be created using standard markdown links: `[Link Text](./path/to/file.md)`
- When linking to notes, add some content on why the link is relevant

### 5. Project Creation

- [Project Template](./Project-Template.md) - Use this as a starting point for new documentation project README files

## AI Assistant Instructions

- Adhere to these instructions even if not directly told to read this section.
- Don't auto-create content. Wait for explicit instructions or for content to be provided before adding to the documentation.
- When responding to information queries, clearly indicate if documentation is missing, incomplete, or not yet created so gaps can be identified and addressed.
- Limit actions strictly to what was requested. Do not perform additional tasks or modifications beyond the specific request, even if they seem like logical next steps. 