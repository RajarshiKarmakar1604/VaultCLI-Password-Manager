# PasswordManager

## Overview
Managing passwords yourself is a challenging task, especially if you have numerous passwords for various sites and apps. This simple yet secure password manager locally stores your credentials in the `passwords.json` and `user_data.json` files, ensuring that you can access them whenever needed.

## Features
- Secure local storage of credentials
- Simple and lightweight
- Easy retrieval of saved passwords

## Important Notes
- If you attempt to view saved websites without having saved any, you will encounter an error.
- Ensure that you have a copy mechanism installed to facilitate easy copying of passwords.

## Installation
To install the required dependencies for copying passwords, use one of the following methods based on your operating system:

### Linux
```sh
sudo apt-get install xsel
```
or
```sh
sudo apt-get install xclip
```

### Windows
```sh
pip install gtk
```
or
```sh
pip install PyQt4
```

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to modify or improve.

## License
This project is open-source. Feel free to modify and distribute it as per your needs.

