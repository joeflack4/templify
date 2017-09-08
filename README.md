# Templify
An engine for creating, extending, and managing system of text file, source code, and data based templates.

## Design Goals
- Temperate living language based.
- Plain text editor in browser
- Two-way data binding for Life preview
- No wysiwyg editor
- When it is saved, it can be saved to the database
- If file system is available, it can save to the file system instead, but save a record in the database
- The record in the database has an ID of the widget, a name, IDs to the components involved, other attributes, and a path link to each of the widgets or at least the final widget
- Stores source code, but also can generate build code recursively if something is updated
