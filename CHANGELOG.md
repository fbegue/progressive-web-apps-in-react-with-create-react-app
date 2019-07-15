# Changelog

All notable changes to "Progressive Web Apps in React with create-react-app” will be documented in this file.

## 1.0.0 - 2019-07-15

### Added

- Created this repository.
- Added this changelog file.
- Added individual lessons as folders to be included under the master branch.

### Changed

- Changed behavior in Chrome's application tab due to Chrome 68 update adds exceptions to the 'Add to homescreen' button which breaks lessons 12 and 13.

- Update `react#16.6.3->16.8.6`.
- Update `react-dom#16.6.3->16.8.6`.
- Update `react-router-dom#4.3.1->5.0.1`.
- Update `react-scripts#2.1.1->3.0.1`.
- Update `workbox#4.0.0-beta.0->5.0.0-alpha.0`
- Changed `workbox.skipWaiting()` to `workbox.core.skipWaiting()` in lessons 4 -> 20 in '/src/sw.js' because of workbox update 4.0.0.
- Changed `workbox.clientsClaim()` to `workbox.core.clientsClaim()` in lessons 4 -> 20 in '/src/sw.js' because of workbox update 4.0.0.

### Removed

- None.
