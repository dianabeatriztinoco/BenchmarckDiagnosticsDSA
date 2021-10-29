# Data Structures and Algorithms
- clone this section to your machine by running `git clone
  https://github.com/appacademy/assessment-for-week-EXIT-version-a-ds-algos-javascript.git`
  ### Setup
- run `npm install` to install dependencies before starting this section.
  ### Testing
- to run this section's tests use `npm test`

## Instructions

### Product of Array Except Self
Please write all code for ths prompt in `./product-of-array-except-self.js`

#### Prompt:
**Given an array `nums` of `n` integers where `n > 1`, return an array output
such that `output[i]` is equal to the product of all the elements of `nums`
except `nums[i]`.**

#### Example:
- Input: `[1,2,3,4]`
- Output: `[24,12,8,6]`

#### Constraints:
It's guaranteed that the product of the elements of any prefix or suffix of the
array (including the whole array) fits in a 32 bit integer.

> Please solve without division and in O(n).

### Longest Non-Repeating Substring
Please write all code for this prompt in `./longest-non-repeating-substring.js`

#### Prompt:
**Given a string, find the length of the longest substring without repeating
characters.**
#### Example 1:
- Input: `"abcabcbb"`
- Output: `3`
- Explanation: The answer is `"abc"`, with the length of `3`.

#### Example 2:
- Input: `"bbbbb"`
- Output: `1`
- Explanation: The answer is `"b"`, with the length of `1`.

#### Example 3:
- Input: `"pwwkew"`
- Output: `3`
- Explanation: The answer is `"wke"`, with the length of `3`.

> Note that the answer must be a substring, "pwke" is a subsequence and not a
> substring.