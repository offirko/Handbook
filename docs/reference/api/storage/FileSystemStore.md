## FileSystemStore

The file system store API provides a lightweight implementation of key/value, get/set based interface (as described in [KVStore]())  on a [file system](https://os.mbed.com/docs/v5.10/apis/filesystem.html) using files. Each key is represented by a single file name, and its value is stored as the file data. 

FileSystemStore's constructor receives the FileSystem instance it will operate with.  FileSystemStore will store all of its keys (files) in a single directory (as configured by ..) 

### FileSystemStore class reference

[![View code](https://www.mbed.com/embed/?type=library)](http://os-doc-builder.test.mbed.com/docs/development/mbed-os-api-doxy/classmbed_1_1_file_system.html)

### FileSystemStore example

[![View code](https://www.mbed.com/embed/?url=https://os.mbed.com/teams/mbed-os-examples/code/FileSystemStore_example/)](https://os.mbed.com/teams/mbed_example/code/FileSystemStore_example/file/375857320a2e/main_example_fsst.cpp/)


### Related content

- [Storage configuration](/docs//development/reference/configuration-storage.html).
- [LittleFS File System](https://os.mbed.com/docs/v5.10/apis/littlefilesystem.html).
- [FatFS File System](https://os.mbed.com/docs/v5.10/apis/fatfilesystem.html).
