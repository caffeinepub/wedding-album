# Wedding Album

## Current State
New project. No existing code.

## Requested Changes (Diff)

### Add
- Wedding album website with beautiful photo gallery display
- Admin panel for uploading and managing photos
- Album organization (create albums, add photos to albums)
- Public gallery view for guests to browse photos
- Individual photo lightbox/fullscreen view
- Couple name and wedding date displayed prominently
- Photo captions support

### Modify
N/A

### Remove
N/A

## Implementation Plan
1. Use blob-storage for photo file storage
2. Use authorization for admin access control
3. Backend: store album metadata, photo metadata (title, caption, album, upload date), couple info
4. Backend: CRUD for albums and photos
5. Frontend public view: hero section with couple name/date, gallery grid, lightbox viewer
6. Frontend admin panel: login, upload photos, create albums, manage/delete photos
