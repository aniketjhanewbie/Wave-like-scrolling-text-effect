# Wave-like-scrolling-text-effect

🔷 Overall Purpose
It creates animated text that scrolls horizontally across the screen in a wavy sine curve pattern. When the user hovers over the text, the wave effect flattens, and the text stops scrolling, giving an interactive and modern look.

🧠 Key Features & Behaviors
✅ Wave Text Animation
Each letter of "LANCERCREEK" is positioned in a sine wave pattern using JavaScript.

The wave is calculated using Math.sin() and Math.cos() for vertical positioning and rotation, giving a fluid wavy feel.

✅ Horizontal Scrolling
The entire word scrolls from right to left continuously using the @keyframes waveScroll animation.

The scroll distance is dynamically set based on the text's full width.

✅ Pause on Hover
When the user hovers over the text:

The wave flattens (letters align horizontally, no sine wave).

Scrolling stops (animation is paused).

A highlight effect is applied with a glowing text shadow and brighter gradient.

✅ Smooth Transition
Transitions ensure smooth switching between wavy and flat states on hover and mouse leave.

🎨 Styling Details
Uses IBM Plex Mono font for a retro/tech aesthetic.

Gradient fill: Letters appear with a horizontal gradient.

Transparent background: Ideal for overlaying on videos or images.

Text shadow: Adds subtle depth and glow effect on hover.

📦 How the Code Works (Step-by-Step)
Section	Function
HTML	- Loads Google Fonts
- Sets up a container for the animated text.
CSS	- Styles body to center content
- Creates animated wave scrolling
- Styles individual letters with gradients and transitions.
JavaScript	- Reads the word "LANCERCREEK"
- Splits it into individual <span> elements
- Calculates positions for wave and flat states
- Applies initial wave layout
- Adds hover interactivity to switch between states
- Dynamically adjusts the scroll distance for precise animation.

🧪 Example Use Case
This could be used for:

A developer or designer portfolio,

A website header with animated branding,

A tech or creative landing page.

🛠️ You Can Customize
Text content: Change "LANCERCREEK" to anything.

Font size, wave amplitude, spacing.

Animation speed (animation: waveScroll 20s linear infinite).

Styling on hover.
