# UI Coverage (Progress: 20/20)
Legend: [ ] not yet tested  -  [x] test written and passing  -  [~] intentionally skipped (reason)

## Pages / Routes
- [x] `/` - All todos page: main layout, h1 title, input present
- [x] `/active` - Active filter page: only uncompleted todos shown
- [x] `/completed` - Completed filter page: only completed todos shown
- [x] `*` - 404 Not Found page: unknown route shows "Page Not Found"

## Add Todo Flow
- [x] Add todo via Enter key: type text, press Enter, item appears in list
- [x] Add todo trimmed: leading/trailing spaces stripped on submit
- [x] Empty input ignored: pressing Enter with empty/whitespace input does not add todo
- [x] Input cleared after add: input field resets to empty after adding

## Todo Item Interactions
- [x] Toggle complete: checking checkbox marks todo as completed (strikethrough style)
- [x] Toggle uncomplete: unchecking checkbox on completed todo restores it to active
- [x] Delete todo: clicking destroy button removes the item (hover required to reveal)
- [x] Edit todo (enter edit mode): clicking label activates edit input
- [x] Edit todo (save with Enter): changes text and exits edit mode
- [x] Edit todo (save with Escape): exits edit mode keeping changes
- [x] Edit todo (blur to save): clicking away commits the edit
- [x] Edit todo (empty text deletes): clearing text and blurring removes the item

## Footer / Filters
- [x] Item count display: shows correct count of active (uncompleted) todos
- [x] Toggle-all checkbox: marks all todos complete; unchecks all when all complete
- [x] Clear completed button: appears only when there are completed todos; removes them
- [x] Filter links active state: selected filter link gets "selected" CSS class

## Persistence
- [x] LocalStorage persistence: todos survive page reload
