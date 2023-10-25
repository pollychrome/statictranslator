# statictranslator

Certainly! Here's the README content in a format that's easy to copy and paste:

---

# StaticTranslator

## Introduction
This utility was created to help developers working with Flutter and the `easy_localization` package efficiently manage and translate their localization files. The primary goal is to make the process of translating your `en.json` (English localization file) into various other languages seamless and straightforward.

StaticTranslator uses OpenAI's GPT-4 model to translate text. This tool currently supports multiple languages, including Brazilian Portuguese, Spanish, Hindi, German, Arabic, French, Turkish, Italian, Persian, and Polish. Languages can easily be added or removed by updating the array. 

## Features
- **Batch Translation**: Handles large localization files by splitting them into manageable batches.
- **Multiple Language Support**: Translates to several languages, following the naming conventions of easy_localizations https://pub.dev/packages/easy_localization.

## Getting Started

### Prerequisites
- Python 3.6 or higher.
- OpenAI API key (you can obtain it from [OpenAI](https://beta.openai.com/signup/)).


### Usage
Run the script by specifying the source JSON file and your OpenAI API key:
```
python3 statictranslator.py <path_to_en.json> --api_key YOUR_API_KEY
```
By default, translated files are saved in the `./translations` directory. You can change the output directory with the `--output_dir` flag.

### Example
```
python3 statictranslator.py en.json --api_key abc123def456
```

## License
This project is open source and available under the [MIT License](LICENSE).
