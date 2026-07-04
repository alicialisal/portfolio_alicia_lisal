# Design System: Alicia Juanita Lisal Portfolio
**Project ID:** 820359330599433519

## 1. Visual Theme & Atmosphere
A modern, tech-noir aesthetic that feels simultaneously airy and dense. The atmosphere merges editorial elegance with precise, futuristic brutalism, creating a high-contrast environment. It relies on deep, inky blacks illuminated by soft, pulsating, and atmospheric glows, giving a subtle glassmorphism depth. The design emphasizes sharp geometric edges and minimalist layout, producing an outcome that feels highly technical yet meticulously crafted.

## 2. Color Palette & Roles
* **Inky Obsidian Black (#050505):** Used as the primary base background color, providing infinite depth and stark contrast.
* **Electric Coral (#FF6F61):** Used for primary accents, glowing elements, button backgrounds, and key decorative typography.
* **Soft Sunset Orange (#FF8C42):** Used for hover interactions, secondary accents, and the wide, diffused background ambient gradients.
* **Crisp Frost White (#e5e2e1):** Used for primary body text, active navigation elements, and high-contrast headings.
* **Muted Zinc Grey (#c9c6c5 & #71717a):** Used for secondary body text, metadata labels, and subtle dividing borders.
* **Charcoal Surface (#131313 to #353535):** Used for elevated project cards, image containers, and minor section background offsets.

## 3. Typography Rules
* **Headlines & Display:** Uses *Newsreader* (serif). High contrast, often italicized for an editorial, sophisticated touch. Used for large display text (`display-xl`) and main section headers.
* **Body Text:** Uses *Epilogue* (sans-serif). Clean, highly legible, and modern. Used for reading paragraphs and narrative text.
* **Labels & Accents:** Uses *Space Grotesk* (sans-serif). Employs heavy letter-spacing (tracking between `0.2em` and `0.3em`) and all-caps styling to give a highly technical, engineered, and architectural feel. Used for buttons, metadata, navigation, and small section labels.

## 4. Component Stylings
* **Buttons:** Sharp, squared-off edges (no border radius). Often feature a solid Electric Coral background or a transparent "ghost" style with a crisp white border. Hover states lift the button slightly with a soft, diffused coral shadow and shift colors to Soft Sunset Orange.
* **Cards/Containers:** Sharp, squared-off edges with subtle, barely-there borders (e.g., white at 5% or 10% opacity). They maintain flat depth by default but gain glowing, electric ambient drop shadows on hover.
* **Background Atmosphere:** Continuous, soft, fixed radial gradients and animated, slow-pulsing circular blobs that float behind the main content, providing a deep, layered volumetric feel.
* **Images & Media:** Often styled with high-contrast grayscale or reduced brightness by default, returning to full vibrant color and slightly scaling up on hover to reward interaction.

## 5. Layout Principles
* **Whitespace & Grid:** Employs generous, airy section gaps (`160px` typically) and wide margins to let content breathe. Adheres to a structured 12-column CSS grid layout for dense content blocks.
* **Alignment:** A deliberate mix of strict left-alignment for long-form narrative content and structured center-alignment for hero statements and major calls-to-action.
* **Navigation:** Fixed, semi-transparent top bar with a glassmorphism blur effect (`backdrop-blur-sm`), allowing the deep, colorful background gradients to subtly shine through while scrolling.
