# Emoji String Converter

A Python GUI application that converts text to emoji sequences and vice versa, using base64 encoding and a predefined set of emojis.

## Features

- **Text to Emoji Encoding**: Convert any text into a sequence of emojis
- **Emoji to Text Decoding**: Convert emoji sequences back to original text
- **Clipboard Integration**: Copy/paste functionality for both text and emoji fields
- **User-Friendly Interface**: Clean Tkinter GUI with intuitive controls
- **Large Emoji Set**: Supports conversion using 256 different emoji characters

## How It Works

1. **Encoding Process**:
   - Text is encoded to UTF-8 bytes
   - Bytes are converted to base64
   - Each base64 byte is mapped to an emoji from the predefined set

2. **Decoding Process**:
   - Emojis are mapped back to their corresponding byte values
   - Bytes are decoded from base64
   - Original text is reconstructed from UTF-8

## Requirements

- Python 3.x
- Tkinter (usually included with Python)
- pyperclip (`pip install pyperclip`)

## Usage

1. Enter text in the "Normal Text" field
2. Click "Encode to Emoji" to convert to emoji sequence
3. Or paste emojis in the "Emoji Text" field
4. Click "Decode from Emoji" to convert back to text
5. Use the copy/paste buttons for easy text transfer

---

## Example Usage

### Basic Conversion

```plaintext
Original Text:  "hi, how are you"
Encoded Emojis: "😈😑👾😽🫠😑💀😾👺🙊🤫💀👹🎃😵‍💫👻🤡🤐😰😡"
```
