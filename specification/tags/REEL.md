# Tag specification: `<REEL>`

## Purpose

The `<REEL>` tag is the top level tag that declares the scope of a REEL document.

## Category

The `<REEL>` tag classifies as:
  - Container tag
  - Meta tag

## Basic usage
```xml
<REEL>
  ...
</REEL>
```

## Attributes

### `version` (default: `1.0`)

__Usage__

The `version` attribute SHOULD be used to reference the REEL version of the REEL document. This will help renderers to determine, which rendering methods to use for the provided content.

If used, the value SHOULD be a valid version string. (TODO define units for version string)

__Example__
```xml
<REEL version="1.0">
  ...
</REEL>
```

## Requirements

### Non-self-closing

The `<REEL>` tag MUST always consist of an opening and closing tag.

### Prohibited cascading

The `<REEL>` tag MUST NOT be used within another `<REEL>` tag

## Changelog

- Added in REEL version 1.0
