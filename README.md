# Abstract Cleaner

This HTML/JavaScript script, is a simple web tool designed to clean up abstracts or other text that has been copied from PDFs or other sources, especially those with common formatting artifacts such as broken Swedish letters, hyphenated line breaks, and mangled paragraph structure. The script allows users to paste the problem text into a text area, click "Fix," and then view or copy the cleaned text.

### Important

When using this tool with DiVA, always copy and paste the text directly from the thesis PDF file, not from the abstract field in the DiVA record. This ensures that the formatting and structure are preserved as they appear in the original document, which is important for accurate cleaning and review.

### What the Script Does

- **Restores Swedish Letters:** The script corrects Swedish characters (ä, ö, å, etc.) that are often corrupted during copy-paste from PDFs, such as "¨o" or "˚a" being replaced with "ö" and "å" respectively.
- **Handles Line Breaks and Hyphenation:** The script joins words split by hyphens at the end of lines (e.g., "exam-\nple" becomes "example") and restores spaces between words that were accidentally joined by line breaks.
- **Normalizes Punctuation and Paragraphs:** The script adds spaces after sentence-ending punctuation and capital letters, restores proper paragraph breaks, and removes extra line breaks.
- **Interface:** The tool provides a text area for input, a "Fix" button to process the text, a "Reset" button to clear the fields, and a "Copy cleaned abstract" button to copy the cleaned output.


### Limitations of the Script

- **Limited to Swedish/Latin Characters:** The script is tuned for Swedish and English characters, but may not handle all possible artifacts or special characters from other languages, especially those outside the Latin alphabet.
- **Relies on Regular Expression Patterns:** The cleaning logic is based on hardcoded regular expressions, so uncommon or highly irregular formatting artifacts may not be handled correctly.
- **No Contextual Understanding:** The script does not understand the meaning of the text, so compromises like hyphen removal or whitespace fixes may occasionally merge words incorrectly or miss context-specific nuances.
- **No Support for HTML or Markup:** The script is designed for plain text and does not handle or clean up HTML, LaTeX, or other embedded markup within the abstract.
- **No OCR or Image Processing:** The script cannot process images or scanned text; it only works with text that has already been copied as plain text, including any OCR artifacts.

### Usage

### Disclaimer

This tool automatically cleans and reformats text copied from PDFs, but it may not perfectly preserve all original formatting, paragraph breaks, or special characters. Always review the cleaned text thoroughly and compare it with the original PDF to ensure accuracy, especially regarding paragraph structure and any unique formatting. The tool is provided for convenience and should not replace careful manual checking.

### Contact

Bugs and suggestions can be sent to Anders Wändahl aw@kth.se
