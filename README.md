# System.CommandLine 
## How to use this scl 

- scl quotes read --file sampleQuotes.txt --delay 40 --fgcolor red --light-mode
- scl quotes add "Hello world!" "Nancy Davolio"
- scl quotes delete --search-terms David "You can do" Antoine "Perfection is achieved"

## Options 
- dotnet run scl quotes read 
``` Description: Work with a file that contains quotes
Usage:
 scl quotes [command] [options]
Options:
 --file <file>  An option whose argument is parsed as a FileInfo [default: sampleQuotes.txt]
 -?, -h, --help Show help and usage information
Commands:
 read             Read and display the file.
 delete            Delete lines from the file.
 add, insert <quote> <byline> Add an entry to the file. ```