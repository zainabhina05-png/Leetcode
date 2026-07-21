# LeetCode Solutions

My solutions to LeetCode problems, written in C++, JavaScript/TypeScript, as part of daily DSA practice.

## 📂 Structure

Solutions are organized by topic. Each folder contains the problem's solution file plus a short note on approach and complexity.

```
leetcode/
├── arrays/
├── strings/
├── linked-lists/
├── trees/
├── graphs/
├── dynamic-programming/
├── backtracking/
├── heaps/
├── binary-search/
├── stacks-queues/
└── two-pointers/
```

Each solution file follows the pattern:

```
<problem-number>-<problem-slug>.ts
```

e.g. `1-two-sum.ts`, `200-number-of-islands.ts`

## 📝 Solution format

Every file includes a header comment like this:

```ts
/**
 * 1. Two Sum
 * https://leetcode.com/problems/two-sum/
 *
 * Approach: Hash map to store seen values and their indices.
 * Time: O(n)  |  Space: O(n)
 */

function twoSum(nums: number[], target: number): number[] {
  const seen = new Map<number, number>();
  for (let i = 0; i < nums.length; i++) {
    const complement = target - nums[i];
    if (seen.has(complement)) return [seen.get(complement)!, i];
    seen.set(nums[i], i);
  }
  return [];
}
```

## 📊 Progress

| Difficulty | Solved |
| --- | --- |
| 🟢 Easy | 0 |
| 🟡 Medium | 0 |
| 🔴 Hard | 0 |
| **Total** | **0** |

## 📌 Problem Log

| # | Title | Difficulty | Topic | Solution |
| --- | --- | --- | --- | --- |
| 1 | Two Sum | Easy | Arrays | [link](./arrays/1-two-sum.ts) |

## 🛠 Running / Testing Locally

```bash
git clone https://github.com/<your-username>/leetcode.git
cd leetcode
npm install
```

Run a single solution:

```bash
npx ts-node arrays/1-two-sum.ts
```

Run tests (if using a test file per solution):

```bash
npm test
```

## 🎯 Goals

- [ ] Solve at least 3 problems a week
- [ ] Cover all core topics at least once
- [ ] Revisit and optimize old solutions as new patterns are learned

## 📚 Resources

- [LeetCode](https://leetcode.com/)
- [NeetCode roadmap](https://neetcode.io/roadmap)
- [Big-O Cheat Sheet](https://www.bigocheatsheet.com/)

---

*Consistency > intensity. Small daily progress beats occasional binges.*

<!---LeetCode Topics Start-->
# LeetCode Topics
## Math
|  |
| ------- |
| [0067-add-binary](https://github.com/zainabhina05-png/Leetcode/tree/master/0067-add-binary) |
| [1979-find-greatest-common-divisor-of-array](https://github.com/zainabhina05-png/Leetcode/tree/master/1979-find-greatest-common-divisor-of-array) |
| [3312-sorted-gcd-pair-queries](https://github.com/zainabhina05-png/Leetcode/tree/master/3312-sorted-gcd-pair-queries) |
| [3336-find-the-number-of-subsequences-with-equal-gcd](https://github.com/zainabhina05-png/Leetcode/tree/master/3336-find-the-number-of-subsequences-with-equal-gcd) |
| [3658-gcd-of-odd-and-even-sums](https://github.com/zainabhina05-png/Leetcode/tree/master/3658-gcd-of-odd-and-even-sums) |
| [3754-concatenate-non-zero-digits-and-multiply-by-sum-i](https://github.com/zainabhina05-png/Leetcode/tree/master/3754-concatenate-non-zero-digits-and-multiply-by-sum-i) |
| [3756-concatenate-non-zero-digits-and-multiply-by-sum-ii](https://github.com/zainabhina05-png/Leetcode/tree/master/3756-concatenate-non-zero-digits-and-multiply-by-sum-ii) |
## String
|  |
| ------- |
| [0067-add-binary](https://github.com/zainabhina05-png/Leetcode/tree/master/0067-add-binary) |
| [1081-smallest-subsequence-of-distinct-characters](https://github.com/zainabhina05-png/Leetcode/tree/master/1081-smallest-subsequence-of-distinct-characters) |
| [3499-maximize-active-section-with-trade-i](https://github.com/zainabhina05-png/Leetcode/tree/master/3499-maximize-active-section-with-trade-i) |
| [3756-concatenate-non-zero-digits-and-multiply-by-sum-ii](https://github.com/zainabhina05-png/Leetcode/tree/master/3756-concatenate-non-zero-digits-and-multiply-by-sum-ii) |
## Prefix Sum
|  |
| ------- |
| [3312-sorted-gcd-pair-queries](https://github.com/zainabhina05-png/Leetcode/tree/master/3312-sorted-gcd-pair-queries) |
| [3756-concatenate-non-zero-digits-and-multiply-by-sum-ii](https://github.com/zainabhina05-png/Leetcode/tree/master/3756-concatenate-non-zero-digits-and-multiply-by-sum-ii) |
## Array
|  |
| ------- |
| [0001-two-sum](https://github.com/zainabhina05-png/Leetcode/tree/master/0001-two-sum) |
| [1260-shift-2d-grid](https://github.com/zainabhina05-png/Leetcode/tree/master/1260-shift-2d-grid) |
| [1331-rank-transform-of-an-array](https://github.com/zainabhina05-png/Leetcode/tree/master/1331-rank-transform-of-an-array) |
| [1979-find-greatest-common-divisor-of-array](https://github.com/zainabhina05-png/Leetcode/tree/master/1979-find-greatest-common-divisor-of-array) |
| [2144-minimum-cost-of-buying-candies-with-discount](https://github.com/zainabhina05-png/Leetcode/tree/master/2144-minimum-cost-of-buying-candies-with-discount) |
| [3312-sorted-gcd-pair-queries](https://github.com/zainabhina05-png/Leetcode/tree/master/3312-sorted-gcd-pair-queries) |
| [3336-find-the-number-of-subsequences-with-equal-gcd](https://github.com/zainabhina05-png/Leetcode/tree/master/3336-find-the-number-of-subsequences-with-equal-gcd) |
| [3534-path-existence-queries-in-a-graph-ii](https://github.com/zainabhina05-png/Leetcode/tree/master/3534-path-existence-queries-in-a-graph-ii) |
## Greedy
|  |
| ------- |
| [1081-smallest-subsequence-of-distinct-characters](https://github.com/zainabhina05-png/Leetcode/tree/master/1081-smallest-subsequence-of-distinct-characters) |
| [2144-minimum-cost-of-buying-candies-with-discount](https://github.com/zainabhina05-png/Leetcode/tree/master/2144-minimum-cost-of-buying-candies-with-discount) |
| [3534-path-existence-queries-in-a-graph-ii](https://github.com/zainabhina05-png/Leetcode/tree/master/3534-path-existence-queries-in-a-graph-ii) |
## Sorting
|  |
| ------- |
| [1331-rank-transform-of-an-array](https://github.com/zainabhina05-png/Leetcode/tree/master/1331-rank-transform-of-an-array) |
| [2144-minimum-cost-of-buying-candies-with-discount](https://github.com/zainabhina05-png/Leetcode/tree/master/2144-minimum-cost-of-buying-candies-with-discount) |
| [3534-path-existence-queries-in-a-graph-ii](https://github.com/zainabhina05-png/Leetcode/tree/master/3534-path-existence-queries-in-a-graph-ii) |
## Two Pointers
|  |
| ------- |
| [3534-path-existence-queries-in-a-graph-ii](https://github.com/zainabhina05-png/Leetcode/tree/master/3534-path-existence-queries-in-a-graph-ii) |
## Binary Search
|  |
| ------- |
| [3312-sorted-gcd-pair-queries](https://github.com/zainabhina05-png/Leetcode/tree/master/3312-sorted-gcd-pair-queries) |
| [3534-path-existence-queries-in-a-graph-ii](https://github.com/zainabhina05-png/Leetcode/tree/master/3534-path-existence-queries-in-a-graph-ii) |
## Dynamic Programming
|  |
| ------- |
| [0799-champagne-tower](https://github.com/zainabhina05-png/Leetcode/tree/master/0799-champagne-tower) |
| [3336-find-the-number-of-subsequences-with-equal-gcd](https://github.com/zainabhina05-png/Leetcode/tree/master/3336-find-the-number-of-subsequences-with-equal-gcd) |
| [3534-path-existence-queries-in-a-graph-ii](https://github.com/zainabhina05-png/Leetcode/tree/master/3534-path-existence-queries-in-a-graph-ii) |
## Bit Manipulation
|  |
| ------- |
| [0067-add-binary](https://github.com/zainabhina05-png/Leetcode/tree/master/0067-add-binary) |
| [3534-path-existence-queries-in-a-graph-ii](https://github.com/zainabhina05-png/Leetcode/tree/master/3534-path-existence-queries-in-a-graph-ii) |
## Graph Theory
|  |
| ------- |
| [2685-count-the-number-of-complete-components](https://github.com/zainabhina05-png/Leetcode/tree/master/2685-count-the-number-of-complete-components) |
| [3534-path-existence-queries-in-a-graph-ii](https://github.com/zainabhina05-png/Leetcode/tree/master/3534-path-existence-queries-in-a-graph-ii) |
## Depth-First Search
|  |
| ------- |
| [2685-count-the-number-of-complete-components](https://github.com/zainabhina05-png/Leetcode/tree/master/2685-count-the-number-of-complete-components) |
## Breadth-First Search
|  |
| ------- |
| [2685-count-the-number-of-complete-components](https://github.com/zainabhina05-png/Leetcode/tree/master/2685-count-the-number-of-complete-components) |
## Union-Find
|  |
| ------- |
| [2685-count-the-number-of-complete-components](https://github.com/zainabhina05-png/Leetcode/tree/master/2685-count-the-number-of-complete-components) |
## Hash Table
|  |
| ------- |
| [0001-two-sum](https://github.com/zainabhina05-png/Leetcode/tree/master/0001-two-sum) |
| [1331-rank-transform-of-an-array](https://github.com/zainabhina05-png/Leetcode/tree/master/1331-rank-transform-of-an-array) |
| [3312-sorted-gcd-pair-queries](https://github.com/zainabhina05-png/Leetcode/tree/master/3312-sorted-gcd-pair-queries) |
## Simulation
|  |
| ------- |
| [0067-add-binary](https://github.com/zainabhina05-png/Leetcode/tree/master/0067-add-binary) |
| [1260-shift-2d-grid](https://github.com/zainabhina05-png/Leetcode/tree/master/1260-shift-2d-grid) |
## Enumeration
|  |
| ------- |
| [1291-sequential-digits](https://github.com/zainabhina05-png/Leetcode/tree/master/1291-sequential-digits) |
| [3499-maximize-active-section-with-trade-i](https://github.com/zainabhina05-png/Leetcode/tree/master/3499-maximize-active-section-with-trade-i) |
## Number Theory
|  |
| ------- |
| [1979-find-greatest-common-divisor-of-array](https://github.com/zainabhina05-png/Leetcode/tree/master/1979-find-greatest-common-divisor-of-array) |
| [3312-sorted-gcd-pair-queries](https://github.com/zainabhina05-png/Leetcode/tree/master/3312-sorted-gcd-pair-queries) |
| [3336-find-the-number-of-subsequences-with-equal-gcd](https://github.com/zainabhina05-png/Leetcode/tree/master/3336-find-the-number-of-subsequences-with-equal-gcd) |
| [3658-gcd-of-odd-and-even-sums](https://github.com/zainabhina05-png/Leetcode/tree/master/3658-gcd-of-odd-and-even-sums) |
## Combinatorics
|  |
| ------- |
| [3312-sorted-gcd-pair-queries](https://github.com/zainabhina05-png/Leetcode/tree/master/3312-sorted-gcd-pair-queries) |
## Counting
|  |
| ------- |
| [3312-sorted-gcd-pair-queries](https://github.com/zainabhina05-png/Leetcode/tree/master/3312-sorted-gcd-pair-queries) |
## Stack
|  |
| ------- |
| [1081-smallest-subsequence-of-distinct-characters](https://github.com/zainabhina05-png/Leetcode/tree/master/1081-smallest-subsequence-of-distinct-characters) |
## Monotonic Stack
|  |
| ------- |
| [1081-smallest-subsequence-of-distinct-characters](https://github.com/zainabhina05-png/Leetcode/tree/master/1081-smallest-subsequence-of-distinct-characters) |
## Matrix
|  |
| ------- |
| [1260-shift-2d-grid](https://github.com/zainabhina05-png/Leetcode/tree/master/1260-shift-2d-grid) |
<!---LeetCode Topics End-->