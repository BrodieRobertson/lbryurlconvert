# lbryurlconvert
Simple script to convert a LBRY url between the different formats

## Example

```sh
[user@arch] lbryurlconvert -o lbry://@BrodieRobertson#5/the-case-against-linux-bootstrapping#8
https://open.lbry.com/@BrodieRobertson:5/the-case-against-linux-bootstrapping:8
[user@arch] lbryurlconvert -t lbry://@BrodieRobertson#5/the-case-against-linux-bootstrapping#8
https://lbry.tv/@BrodieRobertson:5/the-case-against-linux-bootstrapping:8
```

> **_NOTE:_** URLs must be formatted correctly otherwise they may not be converted properly 

## Requirements

+ Basic utils (grep, sed, echo)
+ Shell which can interpret POSIX shell script (Dash, Bash, ZSH, etc)

## Usage

```sh
LBRY URL Convert Help Page
    -p <url> convert a lbry url to the protocol format
    -o <url> convert a lbry url to the open.lbry format
    -t <url> convert a lbry url to the lbry.tv format
    -h show this help page
```

## Why

I frequently use LBRY and it's really annoying to try and share links from the application because they're 
formatted for use within the LBRY protocol not within a web browser.
