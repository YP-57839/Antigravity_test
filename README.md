# Prose UI + Storybook + Dhub Starter

This project is a starter template for building documentation and UI components using [Prose UI](https://prose-ui.com), [Storybook](https://storybook.js.org), and [Dhub](https://dhub.dev).

## Quick Start

1.  **Install dependencies:**
    ```bash
    npm install
    ```

2.  **Run Storybook:**
    ```bash
    npm run storybook
    ```
    This will open Storybook locally at http://localhost:6006.

## Using Prose UI

Prose UI provides beautiful styling and components for Markdown/MDX.

### Creating New Stories

Create new `.mdx` files in the `src/stories` directory.

Example `MyPage.mdx`:

```mdx
import { Meta } from '@storybook/addon-docs/blocks';
import { Callout, CodeBlock } from '@prose-ui/react';

<Meta title="Docs/My Page" />

# My Page Title

Content goes here...

<Callout type="info">
  This is a callout!
</Callout>
```

### Available Components

The project is configured to use Prose UI components. You can import them from `@prose-ui/react`:
- Callout
- CodeBlock
- Steps
- Frame
- Image
- Link
- Math (requires configuration)
- etc.

## Dhub Integration

This project produces standard MDX files compatible with Dhub. Connect this repository to Dhub to visually edit your documentation.
