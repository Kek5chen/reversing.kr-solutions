# reversing.kr Solutions
My Project Solutions to reversing.kr crackmes

## Easy Reversing - Fully Reversed
- `Easy_CrackMe.exe`      - Binary, original
- `Easy_CrackMe.exe.idb`  - Binary IDA Database, fully reversed

## EasyUnpackMe - Fully Reversed
- `Easy_UnpackMe.exe`     - Binary, original
- `Easy_UnpackMe.exe.idb` - Binary IDA Database, everything important reversed
- `ReadMe.txt`            - Instructions

### Info:
It was not, at all, necessary to reverse the binary to find the OEP, but i did it anyways because i wanted to see how the unpacker works.
It basically decrypts everything, then executes it afterwards. Execution ends with the packed executable exiting.
I just left super obvious multiples of instructions unreversed. Everything else is fully explained.
