## `ern binarystore remove <descriptor>`

#### Description

* Remove a mobile application binary from the binary store

#### Syntax

`ern binarystore get <descriptor>`

**Parameters**  

`<descriptor>`

A complete native application descriptor (ex: `myapp:android:1.0.0`), representing the mobile application version associated to this binary.

#### Remarks

* This command will only work if the following conditions are met:
  * A binary store server is running
  * There is an active Cauldron
  * The active Cauldron contains proper configuration of the binary store

* If no binary exists in the store for the targeted mobile application version, the command will fail with an appropriate error message

#### Related commands

 [ern binarystore add] | Add a mobile application binary to the binary store  
 [ern binarystore get] | Get a mobile application binary from the binary store

___  

[ern binarystore add]: ./add.md

[ern binarystore get]: ./get.md