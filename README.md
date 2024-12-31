# Tailwind CSS Classes Not Working

This repository demonstrates a bug where some Tailwind CSS classes are not being applied correctly. The issue seems to be related to the order of classes, the use of conflicting classes, or a problem with the Tailwind CSS configuration.

## Bug Report

The following code snippet should render a red div with white text:

```javascript
<div class="bg-red-500 p-4 text-white">
  This should be red
</div>
```

However, the class `bg-red-500` is not being applied.  This could be due to a number of reasons: a missing or incorrect configuration, conflicting classes, or a misunderstanding in how Tailwind works. The solution will demonstrate how to resolve this issue, showing the correct implementation.