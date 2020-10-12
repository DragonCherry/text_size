# text_size

A simple extension to determine TextSpan or String size before render it.

## Getting Started

```
final textHeight = 'text'.height(constrainedWidth: 200, context: context);
final textSpanHeight = TextSpan(text: 'text').height(200);
final textSpanListHeight = textSpanList.height(constrainedWidth: 200, context: context);
```