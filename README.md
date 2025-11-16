# ASCII Art Generator

Convert images into text-based ASCII art with multiple visual styles.

## Overview

Upload any image and convert it to ASCII art using different character sets. Built this in Google Colab also ASCII art is cool and I wanted to see how it works.

## Features

- 4 different ASCII art styles (Detailed, Simple, Blocks, Minimal)
- Automatic aspect ratio adjustment
- Grayscale conversion and brightness mapping
- Downloadable outputs (text file and PNG image)
- Side-by-side style comparison

## How It Works

1. Upload an image in Colab
2. Image is converted to grayscale
3. Resized while maintaining aspect ratio
4. Each pixel brightness mapped to an ASCII character
5. Generates 4 different style variations
6. Download as text or image

## Styles

**DETAILED** - 11 characters (@#S%?*+;:,.) for subtle shading  
**SIMPLE** - 10 characters (@%#*+=-:. ) for clean look  
**BLOCKS** - 5 characters (█▓▒░ ) for modern aesthetic  
**MINIMAL** - 4 characters (#+. ) for bold contrast

## Technologies

- Python 
- PIL/Pillow for image processing
- matplotlib for visualization
- Google Colab for runtime

## Usage

1. Open notebook in Google Colab
2. Run all cells
3. Upload your image when prompted
4. View results in all 4 styles
5. Download text or PNG output

**Best images:** portraits, high contrast photos, logos, simple shapes

## Technical Details

**Character Mapping:**
- Pixels range from 0 (black) to 255 (white)
- Darker pixels get dense characters (@, #)
- Lighter pixels get sparse characters (., space)

**Aspect Ratio:**
- ASCII characters are taller than wide
- Height adjusted by 0.55x for proper proportions

## Notes

This was a fun weekend project built with AI assistance. Wanted to learn how image processing works and ASCII art seemed like a cool way to explore it. The code is straightforward - basically mapping pixel brightness to characters.
