# Image Converter

A lightweight, client-side image converter that converts any image format to JPG, resized to 1080px width. No upload, no server — everything runs in your browser.

## Features

- Drag & drop or browse to upload images
- Converts any format to JPG (HEIC, HEIF, WEBP, TIFF, PNG, BMP, GIF, AVIF, etc.)
- Automatically resizes to 1080px width while maintaining aspect ratio
- Shows original and output dimensions
- Shows file size before and after conversion
- Supports multiple files at once
- Works entirely in the browser — files never leave your device

## Usage

Just open the page, drop your images in, and download the converted files.

## Live Demo

[nuttblog.github.io/jpx](https://nuttblog.github.io/jpx)

## Tech

Plain HTML, CSS, and JavaScript. Uses [heic2any](https://github.com/alexcorvi/heic2any) for HEIC/HEIF support across all browsers.
