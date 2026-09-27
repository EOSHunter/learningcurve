# R7 repository context: learningcurve

This repository contains a **Curve / RV Library** React front-end prototype under `rvlibrary-master/`. It displays a resource collection, recommendations, and search. The repository root is a wrapper around that project.

- `rvlibrary-master/src/App.js` owns page state and filters resources by title, creator, collection, or selected category.
- `rvlibrary-master/src/data/resources.js` holds the checked-in resource catalog; `initState.js` defines initial UI state.
- `rvlibrary-master/src/DiscoverSection.js` renders the search field; `Recommendation.js` renders a recommendation card with placeholder description and image.
- `rvlibrary-master/public/` holds static assets; `rvlibrary-master/curve/` is a checked-in production build.
- `rvlibrary-master/package.json` uses React 16 and Create React App scripts (`start`, `build`, `test`). The README is the default Create React App guide, not a product specification.

This describes the default branch at `924444b279584fd31927c13f6b5fa879bb327263` from 2017. No current service or deployment is established. See [2017 changes](changes/2017-11.md).
