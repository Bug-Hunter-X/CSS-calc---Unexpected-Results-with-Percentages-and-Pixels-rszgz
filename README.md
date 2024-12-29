# CSS calc() Unexpected Behavior
This repository demonstrates a common issue encountered when using the CSS `calc()` function with percentages and pixels. The problem arises from the order of operations and how `calc()` interacts with the containing element's width.  The provided CSS (`bug.css`) shows the unexpected behavior. The solution (`bugSolution.css`) offers ways to resolve this issue.

## Reproducing the Bug
1. Clone this repository.
2. Open `bug.html` in your browser.
3. Observe that the width of the element is not what is expected due to the improper usage of `calc()`.

## Solution
The solution (`bugSolution.css`) demonstrates correcting this issue by setting the containing element's width explicitly, ensuring proper calculation, and providing alternative approaches.