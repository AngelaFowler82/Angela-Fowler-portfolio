[← Back to Portfolio](./README.md)

# Case Study: Fixing a Typeahead Search for Screen Reader Users

## 🧩 Context

On the Department of Veterans Affairs homepage, the typeahead search component was visually functional—but screen reader users were left in the dark. There were no live announcements, no instructions, and no clear way to interact with the dropdown suggestions.

## 🔍 Problem

- Suggestions weren’t announced as users typed
- No indication that options existed or how to select them
- Screen reader focus was easily lost
- The user experience was inaccessible and confusing—especially for inexperienced users

## ⚙️ Process

I conducted the initial accessibility audit and documented exactly where things broke down for assistive tech users.

Then I partnered with a skilled and determined developer. Over several iterations, we:

- Implemented ARIA live regions to announce suggestions as they appeared
- Added keyboard focus management so users could arrow through options
- Included a short instructional message announced when the field was first focused

## 🎯 Outcome

The final version of the component allowed screen reader users to:

- Understand the field’s purpose and behavior
- Type a search term and hear valid suggestions
- Navigate and select options without confusion

The experience went from *“Where am I and what’s happening?”* to *“Type, arrow, select—done.”* Simple, usable, and no longer a barrier.

---

[← Back to Portfolio](./README.md)
