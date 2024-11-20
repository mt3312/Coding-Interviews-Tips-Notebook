# Quick tips for coding assessment

## Key Indicators for Using a Set

A `set` is a powerful data structure that can be utilized effectively in many coding problems. Here are the key indicators that suggest you should consider using a set:

1. **You Need Uniqueness:**
   - A `set` is designed to store only unique elements.
   - When a problem asks, "Are there any duplicates?" or "Does an element appear more than once?", it's a strong clue that a `set` can help.

2. **Efficient Membership Checks:**
   - If the problem involves repeatedly checking if an element exists, a `set` is very efficient since membership checks are \(O(1)\) on average.

3. **You Don't Need Ordering:**
   - A `set` doesn't preserve the order of elements. If ordering isn't required in the problem, it's safe to consider using a `set`.

## When to Use a Dictionary vs Other Structures

#### Use a Dictionary:
- If the problem involves counting frequencies or mapping relationships.
- **Example**: Comparing character counts for two strings.

#### Use a Set:
- If you only care about the uniqueness of elements, not their counts.
- **Example**: Checking for duplicates in a list.

#### Use a List:
- If you need ordered or indexed storage and are not performing frequent membership checks.
