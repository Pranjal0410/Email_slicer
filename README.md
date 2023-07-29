# Email Slicer

The Email Slicer is a simple Python script that takes an email address as input and separates the username and domain name parts. It can be useful when you need to extract specific information from an email address or analyze email data.

## Introduction

Email addresses are commonly used for various purposes, and sometimes you may need to extract the username and domain name from them. The Email Slicer is a lightweight Python script that allows you to do just that. By providing an email address, the script will separate the username and domain name, making it easier to work with the individual parts of the address.

## Features

- Separates the username and domain name from the email address.
- Easy-to-use command-line interface.
- Written in Python, making it easily understandable and modifiable.

## Requirements

- Python 3.x

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/email-slicer.git
   cd email-slicer
   ```

2. Make sure you have Python 3.x installed on your system.

## Usage

1. Open a terminal or command prompt.

2. Navigate to the project directory.

3. Run the script with Python and provide the email address as an argument:

   ```bash
   python email_slicer.py user@example.com
   ```

4. The script will output the separated username and domain name:

   ```bash
   Username: user
   Domain: example.com
   ```

## Examples

- Slice the email address "john.doe@example.com":

  ```bash
  python email_slicer.py john.doe@example.com
  ```

  Output:

  ```bash
  Username: john.doe
  Domain: example.com
  ```

## Contributing

Contributions are welcome! If you find any bugs or want to add new features, feel free to open an issue or submit a pull request. Please make sure to follow the code of conduct.

1. Fork the repository.

2. Create your feature branch:

   ```bash
   git checkout -b feature/new-feature
   ```

3. Commit your changes:

   ```bash
   git commit -m 'Add some feature'
   ```

4. Push the branch to your fork:

   ```bash
   git push origin feature/new-feature
   ```

5. Open a pull request on the main repository.
