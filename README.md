usage: email_parser [-h] [-i INPUT_PATH] [-o OUTPUT_PATH]
                    [--input_extensions= INPUT_EXTENSIONS]

Parses raw email messages for "Date Sent", "Sender", "Subject" and outputs
them to a CSV file.

optional arguments:
  -h, --help            show this help message and exit
  -i INPUT_PATH, --input_path= INPUT_PATH
                        Email file or directory with email files in it.
  -o OUTPUT_PATH, --output_path= OUTPUT_PATH
                        Output file path.
  --input_extensions= INPUT_EXTENSIONS
                        Comma separated list of extensions to process when
                        scanning a directory for email files.
