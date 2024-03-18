# Chroma Palette - Text Styling Library

The Chroma Palette is a Python module designed to provide comprehensive text styling capabilities for terminal applications. It utilizes ANSI escape codes to apply various styles, colors, decorations, alignments, and shadow effects to text output, enhancing the visual presentation of terminal-based interfaces.

## Installation

Install the librery by using `pip install chroma-palette`

## Usage

Import the librery by using `from chromapalette import *`

## Features

### Text Styles

- **Bold:** Make text bold and prominent.
  ```python
  styled_text = styled_text("Hello, world!", style=TextStyle.BOLD)
  print(styled_text)
  ```

- **Italic:** Slant text slightly for emphasis.
  ```python
  styled_text = styled_text("Hello, world!", style=TextStyle.ITALIC)
  print(styled_text)
  ```

- **Underline:** Add a line beneath the text.
  ```python
  styled_text = styled_text("Hello, world!", style=TextStyle.UNDERLINE)
  print(styled_text)
  ```

- **Strikethrough:** Draw a line through the text.
  ```python
  styled_text = styled_text("Hello, world!", style=TextStyle.STRIKETHROUGH)
  print(styled_text)
  ```

### Text Colors

Choose from a range of foreground text colors including black, red, green, yellow, blue, magenta, cyan, light gray, dark gray, and more.

- **Example:**
  ```python
  styled_text = styled_text("Hello, world!", color=TextColor.RED)
  print(styled_text)
  ```

### Background Colors

Set background colors for text to improve readability and aesthetics.

- **Example:**
  ```python
  styled_text = styled_text("Hello, world!", background=BackgroundColor.GREEN)
  print(styled_text)
  ```

### Text Decorations

- **Bold:** Make text bold and prominent.
  ```python
  styled_text = styled_text("Hello, world!", decoration=TextDecoration.BOLD)
  print(styled_text)
  ```

- **Dim:** Apply a dim effect to the text.
  ```python
  styled_text = styled_text("Hello, world!", decoration=TextDecoration.DIM)
  print(styled_text)
  ```

- **Italic:** Slant text slightly for emphasis.
  ```python
  styled_text = styled_text("Hello, world!", decoration=TextDecoration.ITALIC)
  print(styled_text)
  ```

- **Underline:** Add a line beneath the text.
  ```python
  styled_text = styled_text("Hello, world!", decoration=TextDecoration.UNDERLINE)
  print(styled_text)
  ```

- **Blink:** Cause the text to blink.
  ```python
  styled_text = styled_text("Hello, world!", decoration=TextDecoration.BLINK)
  print(styled_text)
  ```

- **Reverse:** Reverse the foreground and background colors.
  ```python
  styled_text = styled_text("Hello, world!", decoration=TextDecoration.REVERSE)
  print(styled_text)
  ```

- **Hidden:** Hide the text.
  ```python
  styled_text = styled_text("Hello, world!", decoration=TextDecoration.HIDDEN)
  print(styled_text)
  ```

- **Strikethrough:** Draw a line through the text.
  ```python
  styled_text = styled_text("Hello, world!", decoration=TextDecoration.STRIKETHROUGH)
  print(styled_text)
  ```

### Text Alignments

Align text to the left, center, or right within the terminal window.

- **Example:**
  ```python
  styled_text = styled_text("Hello, world!", alignment=TextAlignment.CENTER)
  print(styled_text)
  ```

### Dynamic Color Selection

Convert RGB color values to ANSI escape codes for dynamic color selection.

- **Example:**
  ```python
  dynamic_color = dynamic_color_selection(255, 0, 0)  # Red
  styled_text = styled_text("Hello, world!", color=dynamic_color)
  print(styled_text)
  ```

### Interactive Help Menu

Display an interactive help menu with detailed information on available features and usage instructions.

- **Example:**
  ```python
  help()
  ```

## License

This project is licensed under the [MIT License](LICENSE).
