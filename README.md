# Cardifolio

Cardfolio: a from-scratch, editable “personal card” app that covers input fields, state management, button interactions, Toast feedback, and a themed gradient background—delivering a complete UI flow.

## Layout Framework & Card Composition
•	Structured the UI with ElevatedCard plus Row/Column/Box: circular avatar on the left, information area on the right.
•	Used Modifier (padding, weight, fillMaxWidth, clip, border, etc.) for responsive layout and clear visual hierarchy.

## Input & State Management
•	Implemented three inputs—Name / Hobby / Age—using OutlinedTextField; managed state with remember { mutableStateOf("") }, and constrained Age to numbers.
•	Showed placeholders when empty and live-updated the card display as the user typed.

## Icons & Readability
•	Added Person / Favorite / Info leading icons in text fields to improve semantics and usability.

## Theming & Background
•	Defined custom light/dark gradients in Theme.kt; applied app-wide background via Surface + Brush.verticalGradient.

## Interaction Controls & Edit Lock
•	Built Edit (enable editing), Show (save/display), and an AssistChip to toggle Editing/Locked;
•	Dynamically enabled/disabled buttons and inputs based on the isEditing state.

## Validation & Feedback (Toast)
•	Ran required-field checks on Show; displayed field-specific prompts if anything was missing; showed “Saved successfully!” when all checks passed.

## Version Control & Submission
•	Initialized Git, developed locally, linked the course repository, and submitted a demo-ready build following the milestone requirements.


## Demo Screenshot
* light theme
<img src="https://github.com/AeAloysius/Cardfolio/blob/master/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202025-09-23%20002907.png" width="300" alt="gameplay pic">

* dark theme
<img src="https://github.com/AeAloysius/Cardfolio/blob/master/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202025-09-23%20002937.png" width="300" alt="gameplay pic">
