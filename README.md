# subfont
一个简易的字体精简工具，支持ttf，otf，支持修改family_name，full_name，subfamily_name，使用方式如下，给参数请使用双引号包围

```bash
usage: subfont.py [--family_name FAMILY_NAME] [--full_name FULL_NAME]
                  [--subfamily_name SUBFAMILY_NAME] [--font_path FONT_PATH]
                  [--output_file OUTPUT_FILE] [--text_file TEXT_FILE] [--help]

Process font files and subset them based on specified parameters.

options:
  --family_name FAMILY_NAME
                        The family name of the font (e.g., 'Arial').
  --full_name FULL_NAME
                        The full name of the font (e.g., 'Arial Bold').
  --subfamily_name SUBFAMILY_NAME
                        The subfamily name of the font (e.g., 'Bold').
  --font_path FONT_PATH
                        The path to the font file (e.g., '/path/to/font.ttf').
  --output_file OUTPUT_FILE
                        The path to the output file (e.g.,
                        '/path/to/output.ttf').
  --text_file TEXT_FILE
                        The path to the text file (e.g., '/path/to/text.txt').
  --help                Show this help message and exit.

```

