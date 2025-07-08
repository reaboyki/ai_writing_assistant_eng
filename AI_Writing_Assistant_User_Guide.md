# AI Writing Assistant - Obsidian Plugin User Guide

## 📋 Table of Contents
1. [Plugin Introduction](#plugin-introduction)
2. [Installation](#installation)
3. [Basic Settings](#basic-settings)
4. [Key Features](#key-features)
5. [Command Usage](#command-usage)
6. [Advanced Settings](#advanced-settings)

---

## 🤖 Plugin Introduction

**AI Writing Assistant** is an Obsidian plugin that provides AI-powered writing assistance. It supports various AI models (OpenAI GPT, Claude, etc.) and offers real-time text completion, Ghost Text features, and customizable writing styles.

### 🌟 Key Features
- **Multiple AI Model Support**: OpenAI GPT-4o, o1, Claude, etc.
- **Real-time Auto-completion**: AI-suggested text while typing
- **Ghost Text**: Preview suggestions with transparent text
- **Custom Writing Styles**: Personalized writing style settings
- **Multi-language Support**: Support for Korean, English, and other languages

---

## 💾 Installation

### Manual Installation
1. Copy the downloaded plugin folder to the `.obsidian/plugins/` folder in your Obsidian vault
2. Restart Obsidian
3. Enable "AI Writing Assistant" in Settings → Community plugins

### Post-Installation Check
- If you see "AI completion ready" in the status bar, the installation was successful

---

## ⚙️ Basic Settings

### Step 1: API Key Setup
To use the plugin, you first need an API key from your AI service:

1. Go to **Settings → Community plugins → AI Writing Assistant → Options**
2. Select your AI service:
   - **OpenAI**: GPT-4o, o1-pro, o1-mini, etc.
   - **Claude**: Claude-4-sonnet, Claude-4-opus, etc.
3. Enter the API key for your selected service

### Step 2: Model Selection
- **Performance First**: o1-pro (highest performance, higher cost)
- **Balanced**: GPT-4o (good performance, moderate cost)
- **Economic**: GPT-4o-mini, o1-mini (lower cost)

### Step 3: Basic Options Setup
- **Enable Auto-completion**: Check (default)
- **Completion Delay**: 1000ms (recommended)
- **Max Completion Length**: 150 tokens (default)
- **Temperature**: 0.7 (creativity level)

---

## 🚀 Key Features

### 1. Auto Text Completion
- **How it works**: AI automatically suggests next text when you stop typing
- **Display method**: Shown as gray transparent text (Ghost Text)
- **Accept method**: `→` key

### 2. Ghost Text Feature
- **Preview**: Display AI suggestions transparently
- **Non-intrusive**: Doesn't interfere with actual typing
- **Instant preview**: Review content before accepting suggestions

### 3. Manual Completion Trigger
- **When**: When auto-completion doesn't activate
- **How**: Hotkey setup / Command usage
- **Purpose**: Force AI completion at specific positions

### 4. Custom Writing Styles
- **Create**: Add in Settings under "Writing Styles" tab
- **Elements**: Name, description, system prompt, tone, formality, creativity
- **Example sentences**: Provide style examples for AI learning

---

## ⌨️ Command Usage

The plugin provides the following commands:

### Basic Commands
| Command | Hotkey | Description |
|---------|--------|-------------|
| **Toggle AI Completion** | - | Toggle auto-completion feature |
| **Trigger AI Completion Manually** | - | Force completion at current position |
| **Accept Ghost Text** | `→` | Accept suggested text |
| **Dismiss Ghost Text** | `Esc` | Ignore suggested text |
| **Clear AI Cache** | - | Clear saved completion cache |

### Hotkey Setup
1. Go to **Settings → Hotkeys**
2. Search for "AI Writing Assistant"
3. Assign hotkeys to desired commands

---

## 🔧 Advanced Settings

### Performance Optimization
```
Completion Delay: 500-2000ms (adjust based on typing speed)
Max Completion Length: 50-300 tokens (adjust based on use case)
Enable Cache: Check (improves speed for repeated requests)
```

### Cost Management
- **Cost by Model**: Check per-token costs in settings
- **Usage Monitoring**: View daily/monthly usage in settings
- **Budget Settings**: Set daily usage limits

### Writing Style Customization
1. **Create Style**:
   ```
   Name: Academic Writing Style
   Description: formal academic writing
   System Prompt: Write in formal academic style with proper citations
   Tone: professional
   Formality: formal
   Creativity: 0.3
   ```

2. **Add Example Sentences**:
   - Add 3-5 sentences written in your desired style
   - AI learns the style for more accurate completions

---

## 🐛 Troubleshooting

### Common Issues

#### 1. AI Completion Not Working
**Symptoms**: Ghost Text doesn't appear when typing
**Solutions**:
- Check if plugin is enabled
- Verify API key is correctly entered
- Check network connection
- Run "Toggle AI Completion" from command palette

#### 2. Ghost Text Not Visible
**Symptoms**: Completion works but preview not visible
**Solutions**:
- Check theme compatibility (transparency issues with some themes)
- Restart Obsidian
- Disable and re-enable plugin

#### 3. API Errors
**Symptoms**: "Invalid API key" or similar errors
**Solutions**:
- Re-verify and re-enter API key
- Check API usage limits
- Confirm selected model is supported by your API key

#### 4. Slow Completion Speed
**Symptoms**: Long response time after completion request
**Solutions**:
- Select lighter model (GPT-4o-mini, o1-mini)
- Reduce max completion length (50-100 tokens)
- Enable cache feature

### Debug Information
1. Check **Settings → Show Debug Info**
2. View detailed logs in developer console
3. Record console messages when issues occur

---

## 📊 Usage Tips

### Effective Usage
1. **Provide Context**: Write enough context for AI understanding
2. **Style Consistency**: Select appropriate writing style per document
3. **Strategic Pausing**: Stop typing where you want completion
4. **Review Habit**: Always review AI suggestions before accepting

### Recommended Settings
```
General Writing: GPT-4o + Temperature 0.7 + 150 tokens
Academic Writing: Claude-3.5-sonnet + Temperature 0.3 + 200 tokens
Creative Writing: o1-pro + Temperature 0.9 + 300 tokens
Quick Notes: GPT-4o-mini + Temperature 0.5 + 100 tokens
```

---

*This guide is based on AI Writing Assistant v1.0.0. Some features or interface may change with plugin updates.*