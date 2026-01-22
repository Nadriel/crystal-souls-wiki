```
# <% tp.file.title %>

## Overview
<% tp.system.prompt("Brief description") %>

## Key Details
- **Type**: <% tp.system.suggest(["Character", "Location", "Organization", "Event", "System"], "What type of element is this?") %>
- **Status**: <% tp.system.suggest(["Idea", "Draft", "Complete", "Needs Review"], "What's the development status?") %>
- **Created**: <% tp.date.now() %>

## Connections
*What does this connect to in your world?*

## Notes
*Detailed information goes here*

---
Tags: #<% tp.system.prompt("Primary tag") %>
```