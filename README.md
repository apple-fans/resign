# resign
codesign alternative for iOS12+, support both Linux/MacOS/IOS/Windows

### Acknowledgement

Thank to <https://github.com/zhlynn/zsign> for providing the source code of zsign, which made one good design. However, because other parts used the third-party codes, this program can not provide the source code, but it can be used for free.

### Machine ID

In order to ensure that the system is used in legal and compliance scenarios, the authorization is added to the program. Please use it in legal and compliance scenarios..

You can get the code:

    resign.[arch] -h
    
    >>> Your License is expired in 2020-01-02 23:59:59!
    >>> Your MachineID is 432098542588E6E0183FFCEF202B5E3B382BA6C9D430081A13F0F2680183FFCEF202B5E3B382BA40!

then copy it to me, I will send you the license.dat, put it into directory with resign.[arch]


### New features

1. Support native IOS applications.

2. Speed up the signature process with cache.

3. write the data on the fly.

4. remove/add the dylib, and also fix the errors in some scenarios

5. both support c/c++(dylib), java(jar) and others scripts to call.
