# File Packer Unpacker (Java)

## Overview

File Packer Unpacker is a versatile Java application designed to streamline the process of packing multiple files into a single archive and later unpacking them to their original state. The project encompasses two primary components: `Packer` for packing files and `Unpacker` for unpacking them.

## Features

### Packer

- **Packing Files:**
  - Choose a source directory containing multiple files to be packed.
  - Specify a name for the packed file to be created.
  - Automatically generates a header for each file, encapsulating its name and size.
  - Efficiently supports various file types.

### Unpacker

- **Unpacking Files:**
  - Unpacks files from a packed file created by the `Packer`.
  - Parses headers to extract individual file names and sizes.
  - Creates individual files in the destination directory with the original content.

## How to Use

### Packer

1. Run the `Packer` class.
2. Input the name of the directory containing files to be packed.
3. Specify a name for the packed file to be created.
4. Observe as the program creates a packed file in the current directory.

### Unpacker

1. Execute the `Unpacker` class.
2. Enter the name of the packed file to be unpacked.
3. Witness the program unpacking files and recreating them in the current directory.

## Important Notes

- **Permissions:**
  - Ensure that the user running the application has the necessary permissions to read from the source directory and write to the destination directory.

- **File Location:**
  - The packed file will be created in the current directory.

## Advanced Usage

### Customization

- Users can customize the project by modifying constants, such as buffer sizes, in the source code.
