# Test Cases

| No. | Test | Steps | Expected result |
|---|---|---|---|
| 1 | Add a valid tree | Fill name, species, place; tap Add my tree | Row appears in log, counters increase, success message shown |
| 2 | Empty form | Tap Add my tree with empty fields | Error message shown, nothing added |
| 3 | One field missing | Leave place empty | Error message shown, nothing added |
| 4 | Planted status | Choose Planted and add | "trees planted" counter increases |
| 5 | Same person, two trees | Add two trees with the same name | "trees pledged" is 2, "people taking part" is 1 |
| 6 | Data stays after refresh | Add a tree, reload the page | Tree is still in the log |
| 7 | Clear log | Tap Clear my log | Log empty, counters 0 |
| 8 | Unsafe text | Enter `<b>test</b>` as a name | Shown as plain text, not formatted |
| 9 | Mobile view | Open on a phone | Layout fits the screen, table scrolls sideways |
