# Map

A **Map** is a data structure that stores elements in  
**key–value pairs**, where each key is unique.

In C++, maps are commonly implemented using:
- `map` (ordered)
- `unordered_map` (hash-based)

## Types of Maps in C++
- `map` → Ordered (Red-Black Tree)
- `unordered_map` → Unordered (Hash Table)
- `multimap` → Allows duplicate keys

## Basic Operations
- Insert a key–value pair
- Access value using key
- Update value
- Delete key
- Search for a key

## Common Applications
- Frequency counting
- Hashing problems
- Caching
- Indexing data
- Fast lookups

## Map Problems Covered
Each file in this folder represents **one map-based DSA problem**.

Examples:
- Frequency of Elements
- First Unique Character
- Two Sum
- Group Anagrams
- Uncommon Words from Two Sentences

## Time Complexity
| Operation | map | unordered_map |
|--------|-----|---------------|
| Insert | O(log n) | O(1) average |
| Search | O(log n) | O(1) average |
| Delete | O(log n) | O(1) average |

---

📌 **Note:**  
Most interview problems prefer `unordered_map` for efficiency.

