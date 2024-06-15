HelloWorld.bin: HelloWorld.bin.txt
	xxd -r HelloWorld.bin.txt > HelloWorld.bin

HelloWorld.bin@preview: HelloWorld.bin
	xxd HelloWorld.bin

HelloWorld.bin@checksum: HelloWorld.bin
	sum HelloWorld.bin
