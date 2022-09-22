# grep-go
    implementation linux grep util

# Usage
    go run grep.go [-flags] [file.txt]
# Supported Flags
**-A** - "after" - print +N strings after match\
**-B** - "before" - print +N strings before match\
**-C** - "context" - print ±N (A+B) strings around match\
**-c** &nbsp;- "count" - print count of matched strings\
**-i** &nbsp;- "ignore-case" - ignore case\
**-v** - "invert" - instead of match, exclude\
**-F** - "fixed" - exact string full-match\
**-n** - "line num" - print number of matched string

![Gopher with magnifier](https://raw.githubusercontent.com/cmetallo42/grep-go/main/image.jpg)
