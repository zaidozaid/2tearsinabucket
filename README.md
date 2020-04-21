# 2tearsinabucket
2tearsinabucket is a S3 bucket enumeration tool written in Go designed to enumerate S3 buckets for a specific target by adding common suffixes that companies use to name S3 buckets. 2tearsinabucket will return any bucket name it finds that returns a 200 or 403 response code. If a 200 response code is returned 2tearsinabucket will give you a list of objects found in the bucket. 2tearsinabucket was designed to run on Kali linux.

**What's Coming?**
- Adding prefix option
- Better go code because this is my first golang project
- Performance enhancements

## Installing

- Requires [awscli](https://docs.aws.amazon.com/cli/latest/userguide/install-linux.html)
- Requires [Go](https://golang.org/dl/)

`go get github.com/Revenant40/2tearsinabucket`

## How To Use:

Examples:
- `./2tearsinabucket -w bucket-names.txt -t target`

Options:
- `-w bucket-names.txt` is your list of suffixes to add to your targets name.
- `-t` is the name of the target you wish to enumerate. 

## Thank you:
Just want to say thank you to the creators of sandcastle.py. This project was heavily inspired by you.

## Donate:
<html>
 <a href="bitcoin:17uctxtsWG3gpyAy6iJ8AVd5rdSjkJH2"><img src="https://i.stack.imgur.com/MnQ6V.png"></a>
 </html>

If this project has scored you a bug bounty and you feel like paying back its much appreciated.
