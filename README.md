# CLIK
![](https://img.shields.io/github/forks/MLSA-SRM/Project-CLIK?style=for-the-badge)
![](https://img.shields.io/github/stars/MLSA-SRM/Project-CLIK?color=purple&style=for-the-badge)
![](https://img.shields.io/badge/contributors-4-orange.svg?style=for-the-badge)

CLIK is a command line interface tool to hide and manage your API keys and Secret/Auth tokens.
This is for project managers for easy management of project-related keys and their distribution.
<br><br>
## How CLIK Works
CLIK provides you with a command line interface that allows you to store your API Keys and Secret/Auth tokens in an encrypted JSON file.
You are provided with an option to either store this key locally in a file, or making a note of it to store it anyway you like.
The encrypted JSON file can safely be uploaded to VCS repositories, meaning access will only be granted to those who have been given the JSON decryption key by you.
You can use the CLIK to also add, remove or modify keys, as and when required.
## Built With:
| Software | Version |
|----------|---------|
| Python 3 | 3.7.1 |
| Visual Studio Code| 1.50.1|

## Support:
| Operating System | Version(s) |
|----------|-------------|
| Microsoft Windows | Windows 10 |
| Apple macOS | 10.15(Catalina), Beta 11.0(Big Sur) |

## Installation
You can either clone this repository or install it via pip
```python
pip install printy
```

## Usage
Once you install CLIK, a short and concise documentation can be found br running the following command on your console:
```python
clik
```
## Initialising the JSON File
To create a new file to store keys type the following command in your console:
```python
clik init
```
Now, you can specify all the keys you want to add in a step by step fashion.
CLIK will automatically encrypt the file for you and generate your encryption key.
Now you can either store the key locally or write it down for safekeeping.
So now, your JSON file containing all your keys is ready for upload on your repository.
## Adding/Subtracting Keys
To add new keys to an existing json file, type the following commands in your console:
<br>
### For Adding Keys:
```python
clik FILENAME add
```

### For Subtracting Keys:
```python
clik FILENAME subtract
```
