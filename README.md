# splitter
Re implementation of the Linux split utility in Go

## Why though
I wanted a way to split a file into X parts without first getting the current size or line count. 

## Install or Download
Head over the releases page to download a precompiled version or build it yourself with `go get https://github.com/jordanpotti/splitter`

## Usage

```
Usage of ./splitter:
  -numb int
        Number of files to split the target file into (default 2)
  -post string
        String to append to the output file
  -pre string
        String to prepend to output file
  -target string
        Target File to split
````

> [!WARNING]
> **Disclaimer:** This repository, including all code, scripts, and documentation contained herein, is provided by NVISO exclusively for educational and informational purposes. The contents of this repository are intended to be used solely as a learning resource. The authors of this repository expressly disclaim any responsibility for any misuse or unintended application of the tools, code, or information provided within this repository.
> Users are solely responsible for ensuring that their use of the repository complies with applicable laws and regulations. The authors of this repository do not provide any warranties or guarantees regarding the accuracy, completeness, or suitability of the contents for any particular purpose.
> If you do not agree with these terms, you are advised not to use or access this repository.
