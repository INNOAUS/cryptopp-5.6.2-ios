cryptopp-5.6.2-ios
==================

Crypto++ 5.6.2 (revision 541) built for ARMv7, ARMv7s, and i386 simulator. The libraries were built using the iOS 6.1 SDK. The ZIP includes one common set of headers and one fat libcryptopp.a with the three architectures.

If you only want to include, compile, and link, then only download cryptopp-5.6.2-ios.zip. It has everything you need for an Xcode or command line project. Unzip the ZIP archive and place it in a convenient location. Use `unzip -a` to ensure CRLF are handled properly. /usr/local/cryptopp-ios/ is a good location since it is world readable and write protected.

The three images included in this set show you how to configure an Xcode project using the files in the ZIP archive. The images are provided since you probably have a good idea of what you are doing. If you need detailed help, see the wiki page below.

The additional files provided in the set are used to patch the standard Crypto++ distribution and build the fat libcryptopp.a. If you don't care about building libcryptopp.a yourself, then ignore the additional files.

See http://www.cryptopp.com/wiki/IOS_(Command_Line) for details on how the library was built and how to use the library in an Xcode project. If you have questions, then ask on the Crypto++ Users group at https://groups.google.com/forum/#!forum/cryptopp-users.
