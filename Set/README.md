# Set

A **Set** is a data structure that stores **unique elements only**.
Duplicate values are automatically removed.

In C++, sets are used when **uniqueness** is required.

## Types of Sets in C++
- `set` → Ordered (Red-Black Tree)
- `unordered_set` → Unordered (Hash Table)
- `multiset` → Allows duplicate elements

## Basic Operations
- Insert element
- Delete element
- Search element
- Check size
- Clear set

## Common Applications
- Removing duplicates
- Membership testing
- Finding unique elements
- Set operations (union, intersection)
- Fast lookups

## Set Problems Covered
Each file in this folder represents **one set-based DSA problem**.

Examples:
- Contains Duplicate
- Intersection of Two Arrays
- Longest Consecutive Sequence
- Unique Email Addresses

## Time Complexity
| Operation | set | unordered_set |
|--------|-----|---------------|
| Insert | O(log n) | O(1) average |
| Search | O(log n) | O(1) average |
| Delete | O(log n) | O(1) average |

---

📌 **Note:**  
Use `unordered_set` for best performance unless ordering is required.
