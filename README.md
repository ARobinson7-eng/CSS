## Design Tokens in Storybook

### What designers edit
.storybook/tokens.js

### What developers own
- Web Components
- Tailwind classes
- Build tooling

### Rules
- Components never hardcode colors or spacing
- All visual values come from CSS variables
- Storybook is the live editor for tokens

### Why this exists
- Safe designer changes
- No Tailwind config churn
- Easy multi-brand support
