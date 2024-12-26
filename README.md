# React Native FlatList Performance Issue

This repository demonstrates a performance issue with React Native's FlatList component when rendering a large dataset. The app becomes sluggish and unresponsive.

## Problem

The `MyComponent` renders a FlatList with 1000 items.  On lower-end devices or emulators, scrolling becomes very slow and jerky, indicating poor performance.

## Solution

The solution involves using techniques like `windowSize` and `initialNumToRender` to optimize the rendering process of FlatList.  These help avoid rendering all items at once, improving responsiveness.