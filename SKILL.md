---
name: deslopify
description: Find and remove common code and user interface smells in a website or app. Use when the user asks to deslopify, review, or improve generated UI and copy.
---

# Deslopify

For each code and UX smell below, use one subagent each to eliminate it.

Inspect the product before you make changes. Report only the smells that you find. Give each subagent one smell and the relevant files. Ask it to make a focused change. Review each change against the product's purpose and existing design rules. Check the result in the UI at the supported screen sizes. Do not remove a useful feature only because it matches a pattern below.

Use this format for each finding and its repair. Omit the image when it adds no information.

Title
Description
Optional image

—

## Gradients everywhere

Description: Find gradients that have no clear purpose. Remove repeated gradients from buttons and backgrounds. Keep a gradient if it helps the user see state or hierarchy.

—

## Too many colours

Description: Find colours that have no consistent meaning. Use a small palette. Give each status and action a stable colour. Check contrast after the change.

—

## Pulsing badges

Description: Find animated badges and labels that state the obvious. Remove them when the state cannot change or gives no useful information. Keep motion only when it signals a real change.

—

## Fingernail cards

Description: Find cards with a small coloured tab or bar on the edge. Remove the decoration when it has no meaning. Use a clear label or layout if the cards need distinction.

![Example of a card with an edge tab](https://hereticpleb.vercel.app/_astro/fingernail_slop.DBPsSD7P_1sVxsg.webp)

—

## Excess emoji

Description: Find emoji that do not help the user understand an action or state. Remove them from labels, headings, and status text. Use a consistent icon only when needed.

—

## Misaligned elements

Description: Check icons, SVGs, art, labels, and list items. Align them to the same grid and baseline. Check the layout at narrow and wide screen sizes.

—

## Default font choices

Description: Check whether the font fits the product and remains easy to read. Do not use Inter or JetBrains Mono only because they are common defaults. Remove decorative code marks such as `//` when they have no meaning.

—

## Redundant text

Description: Find text that repeats the brief, the build method, or a fact that the user already knows. Remove it or replace it with information that helps the user act.

—

## Glass effects without purpose

Description: Find blur and translucent panels that reduce clarity. Use solid surfaces when they improve contrast and reading. Keep a glass effect only when it supports the design and remains accessible.

—

## Generic claims and hype

Description: Find broad claims, stock slogans, and welcome text that give no useful information. Name the task, result, or next action in plain words. Make tool screens useful before you make them promotional.

—

Source: [10 tells of a slop UI](https://hereticpleb.com/blog/10-tells-of-slop/).
