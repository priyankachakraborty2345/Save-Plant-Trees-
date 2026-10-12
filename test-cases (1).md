# Test Cases

| No. | Test | Steps | Expected result |
|---|---|---|---|
| 1 | Add a valid tree | Plant & Track tab: fill name, species, place; tap Add | Row appears, "trees pledged" goes up, +5 points |
| 2 | Empty form | Tap Add with empty fields | Error message, nothing added |
| 3 | One field missing | Leave place empty | Error message, nothing added |
| 4 | Planted tree | Choose Planted and add | "trees planted" goes up and check-in buttons appear |
| 5 | Mark planted | On a Pledged tree, tap Mark planted | Status changes to Planted |
| 6 | Check-in Alive | Tap Alive on a planted tree | Health shows Alive, +2 points, "alive at last check-in" updates |
| 7 | Check-in Lost | Tap Lost | Health shows Lost, alive count drops |
| 8 | Quiz all correct | Learn tab: answer all 3 correctly, tap Check answers | "3 of 3 correct", +10 points, lesson gets a tick |
| 9 | Quiz repeated | Take the same quiz again with all correct | No extra points |
| 10 | Quiz wrong | Answer one wrong | Message says Try again, no points |
| 11 | Data after refresh | Add a tree, reload the page | Tree, points and ticks are still there |
| 12 | Clear data | Tap Clear my data | Trees, points and ticks reset to 0 |
| 13 | Unsafe text | Enter `<b>test</b>` as a name | Shown as plain text, not formatted |
| 14 | Mobile view | Open on a phone | Layout fits; tables scroll sideways |
