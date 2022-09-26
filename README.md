# resumeio2pdf

This code will download resume from the website [resume.io](https://resume.io/) and saves it as a PDF file in the same folder. (including links).

## Usage

```bash or Terminal (in vscode or any other code editor)
./resumeio2pdf [options] [ID or URL]
./resumeio2pdf https://resume.io/r/SecureID
```

<!-- resumeio2pdf is the fucntion required to call, for downloading your resume.
     TYPE :      ./resumeio2pdf (url of the resume u want to download)
 
IF IT SHOWS AN ERROR OF - {couldn't recognise resumeio2pdf} - THEN

***   TYPE :           go build
Downloads all the packages of GO.
-->


Options:
*  `-pdf` (string)  name of pdf file (default: `SecureID` + `.pdf`)
*  `-sid` (string) SecureID of resume
*  `-url` (string) link to resume of the format: https://resume.io/r/SecureID
*  `-verbose` show detail information
*  `-version` show version
*  `-y`	overwrite PDF file

## How to build an executable file

In brief:
```bash
go build
```

If you don't understand, visit:
* [Download and install Go](https://go.dev/doc/install)
* [Compile and install the application](https://go.dev/doc/tutorial/compile-install)

## It's all complicated for me...

Repository with binary files: https://github.com/sopov/resumeio2pdf.bin

## I don't know what to do with this file

Try googling some like: `how to run a program from command line`

## Other questions

* I am unable to use GO, neither install or run it in any way.  
* Can you just please send me my downloaded resume? 
* Can you make a video tutorial?

Please visit https://resume.io/pricing
