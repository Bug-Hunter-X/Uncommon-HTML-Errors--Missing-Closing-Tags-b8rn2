# Uncommon HTML Errors: Missing Closing Tags

This repository demonstrates two uncommon but problematic HTML errors that can lead to unexpected layout issues and difficult-to-debug problems.

## Bug 1: Missing Closing Tag in Nested Elements

The first example shows a missing closing tag in nested divs, which causes the browser to handle the closing improperly.

## Bug 2: Missing Closing Tag in img Element

The second example demonstrates a missing closing tag for an img element.  While many browsers might handle this gracefully, it's still bad practice and can cause issues with styling or dynamic content manipulation.

## Solution

The `bugSolution.html` file demonstrates the corrected versions of the code.  Always ensure each opening tag has a corresponding closing tag to avoid these issues.