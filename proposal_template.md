# xz compressed archives
## Introduction
Use .xz instead of .gz files.

## Motivation
Brew is too slow. Having smaller downloads will make it faster.

## Proposed solution
Use xz instead of gzip when compressing software archives.
That would be better compressed archives.

## Detailed design
I don't know where is the server infrastructure behind brew.
But the bottles are gz compressed.

## Alternatives considered
I don't know better compression than .xz files.
