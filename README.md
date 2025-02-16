# Expo Image Component URI Loading Error

This repository demonstrates a common issue encountered when using Expo's `Image` component to load images from a URI.  The error typically arises from issues with the image source, network connectivity, or incorrect component usage.

## Problem
The `Image` component fails to load an image when provided with an invalid or inaccessible URI.  This results in a runtime error in your Expo application.

## Solution
The provided solution focuses on verifying the image URL's validity, ensuring network connectivity, and correctly using the `Image` component.  This includes techniques like adding error handling and using placeholders for failed image loads.

## How to reproduce
1. Clone this repository.
2. Run `npm install` to install necessary packages.
3. Run the app using Expo Go or your preferred Expo development environment.
4. Observe the error when the app attempts to load the image from the specified, potentially invalid, URI.

## How to fix
Refer to `bugSolution.js` for the improved implementation that addresses the error.