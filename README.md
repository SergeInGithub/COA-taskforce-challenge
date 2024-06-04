# COA-Taskforce-challenge

## 🧬 Live Site

**_[Live Site](https://coa-taskforce-challenge-test.vercel.app)_**

## ⏯️ Table of Contents

1. [Project Description](#project-description)
2. [Setup Instructions](#setup-instructions)
3. [Usage](#usage)
4. [Coding Challenges](#coding-challenges)
   - [Challenge 1: Subarray with Target Sum](#challenge-1-subarray-with-target-sum)
   - [Challenge 2: String Transformation](#challenge-2-string-transformation)

## ℹ️ Project Description

This project contains two main parts:

1. **Design Part**: A web page with a responsive gallery that adjusts to different screen sizes.
2. **Coding Challenges**: Solutions to two algorithmic problems.

### 💠 Design Part

The web page displays a gallery of images with overlay text that reacts to hover events. The overlay text moves up smoothly on hover and disappears when the screen width is below 1000px.

### 🦾 Coding Challenges

- **Subarray with Target Sum**: Determine if there exists a contiguous subarray within an array that sums up to a target value.
- **String Transformation**: Transform a given string based on specific divisibility rules.

## 📍 Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/SergeInGithub/COA-taskforce-challenge.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd COA-taskforce-challenge
   ```
3. **Open the `index.html` file in a web browser to view the design part**.

## Usage

### 👁️ Viewing the Design Part

1. Open the `index.html` file in a web browser.
2. Hover over the images to see the overlay text move up.
3. Resize the browser window to see the overlay text disappear when the width is below 1000px.

### 🚀 Running the Coding Challenges

You can run the coding challenges in any JavaScript environment (e.g., browser console, Node.js).

#### Challenge 1: Subarray with Target Sum

Example usage:

```javascript
const arr = [4, 2, 7, 1, 9, 5];
const target = 17;
console.log(containsSubarraySum(arr, target)); // Output: true
```

#### Challenge 2: String Transformation

Example usage:

```javascript
console.log(transformString('Hamburger')); // Output: "regrubmaH"
console.log(transformString('Pizza')); // Output: "80 105 122 122 97"
```

## 🦾 Coding Challenges

### Challenge 1: Subarray with Target Sum

Given an array of integers and a target sum, determine if there exists a contiguous subarray within the array that sums up to the target. Return `true` if such a subarray exists, otherwise return `false`.

#### Example:

```javascript
const arr = [4, 2, 7, 1, 9, 5];
const target = 17;
console.log(containsSubarraySum(arr, target)); // Output: true
```

### Challenge 2: String Transformation

Given a string, transform it based on the following rules:

- If the length of the string is divisible by 3, reverse the entire string.
- If the length of the string is divisible by 5, replace each character with its ASCII code.
- If the length of the string is divisible by both 3 and 5 (i.e., divisible by 15), perform both operations in the order specified above.

#### Example:

```javascript
console.log(transformString('Hamburger')); // Output: "regrubmaH"
console.log(transformString('Pizza')); // Output: "80 105 122 122 97"
```
