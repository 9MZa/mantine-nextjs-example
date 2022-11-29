# Mantine 5.8 is out!

This release introduces new `RichTextEditor` component based on Tiptap [(https://tiptap.dev/)](https://tiptap.dev/). `@mantine/tiptap` package is a replacement for `@mantine/rte` (which was built on top of Quill.js).

New `RichTextEditor` component is much more flexible and includes more features than the previous component:
- You fully control the state and behavior with `useEditor` hook
- Each control is exposed as a separate component – you can now change props and styles of each control individually
- All Tiptap extensions are supported – if something is missing, you can easily add a custom control that executes any operation
- It is now possible to include code highlight with `lowlight` package
- New Bubble and Floating menus to display controls

Checkout all new `RichTextEditor` component features:
- Changelog – [https://mantine.dev/changelog/5-8-0/](https://mantine.dev/changelog/5-8-0/)
- Release on GitHub – [https://github.com/mantinedev/mantine/releases/tag/5.8.0](https://github.com/mantinedev/mantine/releases/tag/5.8.0)