# Week 2 Flexbox Practice: Moving Boxes Around the Screen

**Name:** UTUJE Ange Fidele
**Course:** Advanced Frontend Web Development

## Video Demonstration
[Watch the video](PASTE_YOUR_VIDEO_LINK_HERE)

## Live Demo (bonus)
[GitHub Pages link](PASTE_LINK_HERE_IF_YOU_PUBLISH)

## About the Project
Six numbered, colored boxes sit inside a flex container that fills the screen (`width: 100%; height: 100vh;`). A CSS `@keyframes` animation changes `justify-content` and `align-items` so the boxes visit all 9 positions, from Top Left to Bottom Right, on an infinite loop. A second section shows an extra layout with `flex-direction: column` and `flex-wrap: wrap`. HTML and CSS only, no JavaScript.

## Flexbox Properties Used
| Property | What it does |
|---|---|
| `display: flex` | Turns the container into a flex container so its children become flex items. |
| `justify-content` | Aligns items along the **main axis** (horizontal in a row). Values used: `flex-start`, `center`, `flex-end`. |
| `align-items` | Aligns items along the **cross axis** (vertical in a row). Values used: `flex-start`, `center`, `flex-end`. |
| `align-content` | Aligns multiple wrapped lines/columns along the cross axis. Only works when items wrap. |
| `flex-direction` | Sets the main axis. `row` is the default; `column` makes the main axis vertical. |
| `flex-wrap` | Lets items wrap onto new lines or columns when they run out of space. |
| `gap` | Adds space between flex items without using margins. |

## The 9 Positions (flex-direction: row)
| # | Position | CSS |
|---|---|---|
| 1 | Top Left | `justify-content: flex-start; align-items: flex-start;` |
| 2 | Top Center | `justify-content: center; align-items: flex-start;` |
| 3 | Top Right | `justify-content: flex-end; align-items: flex-start;` |
| 4 | Middle Left | `justify-content: flex-start; align-items: center;` |
| 5 | Center | `justify-content: center; align-items: center;` |
| 6 | Middle Right | `justify-content: flex-end; align-items: center;` |
| 7 | Bottom Left | `justify-content: flex-start; align-items: flex-end;` |
| 8 | Bottom Center | `justify-content: center; align-items: flex-end;` |
| 9 | Bottom Right | `justify-content: flex-end; align-items: flex-end;` |

## Extra Layout
`flex-direction: column; flex-wrap: wrap;` with `align-content` animating between `flex-start`, `center` and `flex-end`.

## Screenshots
![Top Left](screenshots/top-left.png)
![Center](screenshots/center.png)
![Bottom Right](screenshots/bottom-right.png)

## How to Run
Open `index.html` in a browser.
