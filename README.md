## How to go about Organizing your CSS

-- Follow Your Team

-- Use comments to create headers / labels inside your css

-- Sort properties alphabetically (Ctrl + P -> '>sort' -> Sort Lines Ascending)

-- Larger projects usually follow a naming convention methodology. Popular naming convention: BEM = Block, Element, Modifier

## BEM Methodology:

-- B - Block: The block is a standalone component in the HTML / CSS e.g., menu. This can be a default semantic HTML element, or possibly a class (like .menu).

-- E - Element: The element is a dependent part of the block (e.g., header__title or header__item). Naming scheme uses dunders (double underscores).

-- M - Modifier: The modifier is a flag / label or signal that 'flags' (hence its name) a variant of a block or element (e.g., btn--large or btn--primary). Naming scheme uses double hyphens.