---
path: '/examples/nesting/drag-sources'
title: 'Drag Sources'
---

[JavaScript](https://github.com/react-dnd/react-dnd/tree/gh-pages/examples_js/03%20Nesting/Drag%20Sources)
[TypeScript](https://github.com/react-dnd/react-dnd/tree/master/packages/examples/src/03%20Nesting/Drag%20Sources)

You can nest the drag sources in one another. If a nested drag source
returns `false` from `canDrag`, its parent will
be asked, until a draggable source is found and activated. Only the
activated drag source will have its `beginDrag()` and
`endDrag()` called.

<nesting-drag-sources></nesting-drag-sources>
