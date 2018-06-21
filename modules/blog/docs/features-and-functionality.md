## Volo.Blog Product Features & Functionalities

The blog module takes Medium as a reference for simplicity & features.

### Overall / Ideas

* Post (Full Audited)
  * Title
  * Content
  * Creator
  * Tags
  * View Count
  * Comments (Full Audited)
    * Text
* Editor
  * Markdown & WYSIWYG editor
  * Supports images, videos and code sections
  * Supports preview
* Users
  * Supports gravatar for profile image
* Supports Multi-Tenancy
* Theming
  * Nicely split views into partials, so we can create templates by overriding some parts.
* ORM/DB
  * Supports EF Core & MongoDB

### Pages

* Post List
  * Shows a list of blog post summaries (title & some part from the beginning)
    * Supports Paging & Searching
    * Ordered by creation time desc (no need to sorting)
  * Link to "new post" page.
* Post Detail
  * Show the post (title, content, tags) and allow to edit/delete.
  * Show the post comments and allow to add/edit/delete.
* New/Edit Post
  * Editor to create a new post or edit an existing post
  * Allow to add tags and other related stuff