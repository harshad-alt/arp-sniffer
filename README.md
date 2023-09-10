----------------------------------------------------------
-h or --help:			Print this help text.
-l or --lookup:			Print the available interfaces.
-i or --interface:		Provide the interface to sniff on.
-v or --version:		Print the version information.
----------------------------------------------------------

Usage: ./arpsniffer -i <interface> [You can look for the available interfaces using -l/--lookup]
```

### How to compile?

1. You should have `libpcap` installed on your linux system. If you don't have, you can do it with the following command

```
$ sudo apt-get install libpcap-dev
```

2. You can compile with the following command

```
$ gcc arpsniffer.c -o arpsniffer -lpcap
