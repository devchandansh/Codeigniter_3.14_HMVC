# Codeigniter HMVC Moduler Extension
Codeigniter  Version 3.14 HMVC

# Basic HMVC Structure

It is the Basic Codeigniter HMVC Structure

```
/application
	/controllers
   	/config
   	/helpers
   	/language
   	/libraries
   	/models
	/modules
		/module
			/controllers
			/config
			/helpers
			/language
			/libraries
			/models

   	/third_party
   	/views
```

# Instruction:

--	First, Place `thirs_party` folder files into `application/third_party`  folder
--	Second,Place `core` folder's files into `application/core` folder

# Note:

Modules Name & Controller Name Must be same. Controller name must be `Capitalize` like: `Users.php` 
```
modules/
	/Users
		/controller
			/User.php
```

