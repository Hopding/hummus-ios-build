# Warning
This project works, but is very much a work in progress, and documentation will be lacking.

# Building Static Libraries
Run `chmod +x ./build && ./build` to generate the static library (`.a`) files in `./out`. This will generate `.a` files for the following architectures, as well as a "universal" file that targets all of the architectures:
	* i386
	* x86_64
	* arm64
	* armv7s
	* armv7


**NOTE:** You can now use the `.a` files in other projects. Be sure to set their "Type" to `Macho-O Object Code`!
