
        __  ___                                  ____  _     
       /  |/  ____ _____  ____ _____ ____       / __ \(______
      / /|_/ / __ `/ __ \/ __ `/ __ `/ _ \     / / / / / ___/
     / /  / / /_/ / / / / /_/ / /_/ /  __/    / /_/ / / /    
    /_/  /_/\__,_/_/ /_/\__,_/\__, /\________/_____/_/_/     
                             /____/    /_____/  
			
             coded-by: bakri | twitter: @b7kri_17
	     
	     using  : sudo  manage_dir -option <dir name or full path>
	     Eg     : sudo manage_dir -sort /home/bakri/Downloads
	     option : { --help --sort --delete }
## Describtion
A bash script that manages folders within a Linux system.
Basically a day by arranging the contents of any folder by specifying the extension of the files within the folder and arranging all the files with the same extension in one folder with the extension a name

Or delete a folder with its contents

Note
Dealing with only one folder


## Installation :
- Install with git: `git clone https://github.com/b7kri-17/manage_dir.git`
- Install with ZIP file: [Download here](https://github.com/b7kri-17/manage_dir/archive/refs/heads/main.zip)

## Usage :
- After Download `cd manage_dir/ && sudo chmod +x manage_dir`

- Use  :`sudo manage_dir -option <dir name or full path>`
- E.g  :`sudo manage_dir --sort /home/bakri/Downloads`

## Option :
 - show help | option `sudo manage_dir --help`
 
		      --sort   | -s       :sort file in directory
    	      --delete | -d       :delete directory
              --help   | -h       :how this menu

