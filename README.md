# Bookmark Manager
User stories:
1. As a user, so that I can see what bookmarks have been stored, I would like to see a list of bookmarks.
2. As a user, so that I can save new bookmarks, I would like to add new bookmarks.
3. As a user, so that I can remove any unwanted bookmarks, I would like to be able to delete bookmarks.
4. As a user, so that I can make changes to my existing bookmarks, I would like to be able to update my bookmarks.
5. As a user, so that I can share my thoughts on any bookmarks, I would like to be able to comment on bookmarks.
6. As a user, so that I can organise my bookmarks, I would like to tag bookmarks into categories.
7. As a user, so that I can find bookmarks for a particular category, I would like to filter bookmarks by tag.
8. As a site manager, so that I can upkeep privacy and security standards for the app, I would like users to be restricted to manage only their own bookmarks.

Domain model:

| Objects  | Messages |
|:--------:|:--------:|
| bookmarks| list     |
| bookmarks| add      |
| bookmarks| delete   |
| bookmarks| update   |
| bookmarks| comment  |
| bookmarks| tag      |
| bookmarks| filter   |
| user     | bookmarks|
