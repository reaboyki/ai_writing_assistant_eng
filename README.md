# AI Writing Assistant (Korean)
![Automatic Text Prediction Demo](demo1.gif)

![Usage Demo](demo2.gif)

An Obsidian plugin inspired by Cursor AI's tab functionality. When you pause while typing, the AI automatically analyzes the context and shows you a preview of the next text to come.

To install the Korean version, please visit:
  https://github.com/reaboyki/ai_writing_assistant_ko

## Key Features

### Automatic Text Prediction
When you pause while typing, the AI automatically analyzes the previous and following context (if available) to show you a preview of the next text in gray.

### Simple Controls
- **Accept**: Press the right arrow key `→` if you like the suggestion
- **Ignore**: Continue typing or press `ESC` if you don't like it

## Installation

1. Go to the "Community Plugins" tab in Obsidian settings
2. Turn off "Safe Mode" (if not already disabled)
3. Download or clone this repository
4. Copy the plugin folder to the .obsidian/plugins/ directory in your Obsidian vault folder
5. Restart Obsidian or "Refresh plugins" in settings
6. Enable "AI Writing Assistant" in the Community Plugins list

## Usage

1. Install and activate the plugin
2. Pause briefly while typing text
3. Review the gray text suggested by the AI
4. Press right arrow key `→` to accept or `ESC`/continue typing to ignore

## Features

- **Arrow key instead of Tab**: Uses the right arrow key `→` instead of Tab since it's difficult to prevent indentation when pressing Tab in Obsidian
- **Multiple AI model support**: Choose from various AI models
- **Usage statistics**: Provides approximate estimates (check each API provider's dashboard for accurate billing)
- **Customizable**: Adjust various settings to fit your environment

## File Structure

- `manifest.json`: Configuration file
- `main.js`: Core functionality implementation
- `AI_Writing_Assistant_User_Guide.md`: Detailed usage guide

## Notes

- This is my **first plugin**, so there may be many shortcomings. Please let me know if you find any issues or have suggestions for improvement.
- **Reasoning model response speed**: Reasoning models are quite slow (about 7-15 seconds). For faster responses, I recommend using non-reasoning models instead of the latest models.

## Requirements

- Obsidian v0.15.0 or higher

## Author

Created by [reaboyki](https://github.com/reaboyki)

## Version

1.0.0
