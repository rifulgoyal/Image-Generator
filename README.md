Image Generator
Image Generator is a lightweight web application that allows users to search for keywords and instantly generate relevant visual results. Built with a clean HTML structure, it provides an intuitive interface complete with dedicated search controls, result counters, and dark mode toggling.

Design Decisions:

Explicit Form Controls & Reset Button: Included a dedicated reset (Clear) button alongside the submit button inside the search form to let users clear their queries quickly without manual backspacing.

Persistent Visual Feedback Elements: Embedded dedicated <p> tags for status updates and result counts (Showing "10" results) directly into the DOM structure to ensure immediate state updates without causing UI layout shifts.
