# HTML Learnings Project

This is a simple HTML project created as part of my Udemy HTML learning course. It demonstrates basic HTML structure and includes examples of headings, hyperlinks, images, and tables, lists: ordered lists and unordered lists, forms, buttons, Special symbols.

## Features

- HTML headings (h1 to h6) with inline formatting tags (italic, strikethrough, mark, bold)
- Basic paragraph element
- Hyperlinks with different target behaviors (same tab vs new tab)
- Image elements (including examples with and without src attributes)
- HTML table with headers and data rows
- Created Unordered lists & Ordered lists
- Forms contains firstname, lastname, age, email, password, sumbit button.
- added Selectors: ID, class, data-test for tables, lists & forms.
- created buttons for navigation with selectors
- Used some Special symbols like copyright using numeric like : &#169; or with entity name like: &copy;
- Basic JavaScript example for dynamic content update

## How to View

Simply open the `index.html` file in any web browser to see the page.

## Files

- `index.html`: The main HTML file containing the page structure


## Technologies Used

- HTML5

# 🎯 HTML Selectors for Test Automation

## Selector Types (Priority Order)

| Priority | Attribute | CSS Selector | Stability | Example |
|----------|-----------|--------------|-----------|---------|
| 🥇 **BEST** | `data-testid` | `[data-testid="login-btn"]` | 🔒 **Very High** | `<button data-testid="login-btn">` |
| 🥈 **Good** | `id` | `#main-form` | 🔐 **High** | `<form id="main-form">` |
| 🥉 **Avoid** | `class` | `.btn-primary` | ⚠️ **Low** (changes often) | `<button class="btn-primary">` |

# 🔤 HTML Symbols - Most Common Entities

## Quick Reference Table

| Symbol | Entity Name | Numeric Code | Use Case |
|--------|-------------|--------------|----------|
| © | `&copy;` | `&#169;` | Copyright |
| ® | `&reg;` | `&#174;` | Registered |
| ™ | `&trade;` | `&#8482;` | Trademark |
| € | `&euro;` | `&#8364;` | Euro |
| £ | `&pound;` | `&#163;` | Pound |
| ¥ | `&yen;` | `&#165;` | Yen |
| $ | `$` | `&#36;` | Dollar |
| → | `&rarr;` | `&#8594;` | Right Arrow |
| ← | `&larr;` | `&#8592;` | Left Arrow |
| ↑ | `&uarr;` | `&#8593;` | Up Arrow |
| ↓ | `&darr;` | `&#8595;` | Down Arrow |
| ✓ | `&check;` | `&#10004;` | Checkmark |
| ✗ | `&times;` | `&#10007;` | X Mark |
| ★ | `&star;` | `&#9733;` | Star |
| ♥ | `&hearts;` | `&#9829;` | Heart |
| & | `&amp;` | `&#38;` | Ampersand |
| < | `&lt;` | `&#60;` | Less Than |
| > | `&gt;` | `&#62;` | Greater Than |
| " | `&quot;` | `&#34;` | Quotes |
| ' | `&#39;` | `&#39;` | Apostrophe |
 
## Essential Coding Symbols
| Symbol | Entity | Use |
|--------|--------|-----|
| ½ | `&frac12;` | Fraction |
| ¼ | `&frac14;` | Quarter |
| × | `&times;` | Multiply |
| ÷ | `&divide;` | Divide |
| ° | `&deg;` | Degree |
| ± | `&plusmn;` | Plus/Minus |
| ∞ | `&infin;` | Infinity |

# ⚡ Inline JavaScript Concepts

## What is Inline JavaScript?
Event handlers written **directly inside HTML tags** that execute JavaScript when users interact with elements (clicks, typing, hovering).

## Core Concept: onclick Attribute
The `onclick` attribute contains JavaScript code that runs **immediately when a button/link is clicked**.

## How It Works (Step-by-Step)
1. User clicks button with onclick="..."

2. Browser reads JavaScript inside onclick

3. Code executes instantly

4. Webpage updates (text changes, alerts, etc.)


## Key JavaScript Functions Explained

**`document`** = Entire HTML webpage loaded in browser memory

**`getElementById('id')`** = Search entire page for element with matching ID, returns that element

**`innerHTML`** = Get/set **text content** inside any HTML element

**`Date()`** = Built-in function returning **current date/time** from computer clock (no internet needed)

## Real Example Flow
Button clicked → onclick fires → Finds <p id="date"> → Gets current Date() → Updates paragraph text


## Common Event Types
- `onclick` - Button/link clicks
- `onchange` - Form input changes  
- `onmouseover` - Mouse hover
- `onload` - Page finishes loading

## Why Use Inline JavaScript?
- **Quick prototyping** - No separate files
- **Simple interactions** - Counters, date display
- **Learning tool** - See instant results

## Production Recommendation
For real projects, use `addEventListener()` in external JS files instead of inline attributes.

## QA Testing Connection
Inline JavaScript creates **dynamic content** perfect for automation practice:
- Click button → Verify text changes
- Test date updates
- Practice waiting for dynamic elements

## Key Takeaway
**HTML Structure + Inline JS Events = Interactive Webpage** (no backend needed)




