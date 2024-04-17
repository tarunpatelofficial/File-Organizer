# File Organizer

## Overview
This Python script organizes files in a specified directory based on their file extensions. It categorizes files into different folders based on their types, such as audio, video, image, archive, document, and screenshots. The script uses predefined file extensions to classify files and then moves them to their respective folders.

## Features
- **File Categorization**: Files are categorized into different types based on their file extensions.
- **Moving to Specific Folders**: The script moves files to specific folders based on their types.
- **Screenshot Detection**: Screenshots are identified and moved to a separate folder within the image category.
- **Handling Other Files**: Files that do not belong to any predefined category are moved to an "other" folder.

## How to Use
1. Choose or specify the directory where the files are located.
2. Run the Python script `File Organizer.ipynb`.
3. The script will categorize the files based on their extensions and move them to their respective folders.
4. Review the organized folders to ensure files are correctly categorized.

## Supported File Types
- **Audio**: .aac, .aiff, .flac, .m4a, .mp3, .ogg, .wav, .wma, .amr, .ape, .midi, .au, .ra, .dsd, .opus
- **Video**: .mp4, .mkv, .avi, .mov, .wmv, .flv, .webm, .m4v, .3gp, .ogv, .mpeg, .mpg, .ts, .vob, .rm, .rmvb
- **Image**: .jpg, .jpeg, .png, .gif, .bmp, .tiff, .webp, .svg, .ico, .jfif, .heif, .bat, .raw, .eps
- **Archive**: .zip, .rar, .tar.gz, .tar.bz2
- **Document**: .doc, .docx, .pdf, .txt, .ppt, .pptx, .xls, .xlsx

## Dependencies
This script requires the `os` and `shutil` modules, which are part of the Python standard library.
