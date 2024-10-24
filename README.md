# Bookmark Manager

Idea: This chrome extension is to manage bookmarks from an upstream source in your browser along side of your normal bookmarks

## Features

- [ ] CRUD operations for bookmarks
  - [ ] Create bookmark in browser
  - [ ] Get whether bookmark exists
  - [ ] Update bookmark
  - [ ] Delete bookmark
- [ ] Get list of bookmarks from upstream location
- [ ] Periodically check upstream list of bookmarks
- [ ] Sync bookmarks with upstream

## [Chrome Extensions API](https://developer.chrome.com/docs/extensions/reference/api) Important details

| API | Description |
| --- | --- |
| [`alarms`](https://developer.chrome.com/docs/extensions/reference/api/alarms) | Use the `chrome.alarms` API to schedule code to run periodically or at a specified time in the future. |
| [`bookmarks`](https://developer.chrome.com/docs/extensions/reference/api/bookmarks) | Use the `chrome.bookmarks` API to create, organize, and otherwise manipulate bookmarks. Also see [Override Pages](https://developer.chrome.com/docs/extensions/override), which you can use to create a custom Bookmark Manager page. |
| [`extensionTypes`](https://developer.chrome.com/docs/extensions/reference/api/extensionTypes) | The `chrome.extensionTypes` API contains type declarations for Chrome extensions. |
| [`notifications`](https://developer.chrome.com/docs/extensions/reference/api/notifications) | Use the `chrome.notifications` API to create rich notifications using templates and show these notifications to users in the system tray. |
| [`permissions`](https://developer.chrome.com/docs/extensions/reference/api/permissions) | Use the `chrome.permissions` API to request [declared optional permissions](https://developer.chrome.com/docs/extensions/develop/concepts/declare-permissions) at run time rather than install time, so users understand why the permissions are needed and grant only those that are necessary. |
| [`readingList`](https://developer.chrome.com/docs/extensions/reference/api/readingList) | Use the `chrome.readingList` API to read from and modify the items in the [Reading List](https://support.google.com/chrome/answer/7343019). |
| [`types`](https://developer.chrome.com/docs/extensions/reference/api/types) | The `chrome.types` API contains type declarations for Chrome. |
