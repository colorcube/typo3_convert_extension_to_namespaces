# Convert TYPO3 Extension code to namespaces

Renaming all old TYPO3 class names (t3lib_*, etc.) to new ones with namespaces.
Making a backup file (*.bak) of all modified files.

WARNING: the conversion is done by simple search and replace and might produce wrong results and could break your code!
Review the changed files!

Use at your own risk!!

## Install

typo3_convert_extension_to_namespaces.php is a cli script. PHP has to be installed as cli.
    
You can run the script with php
    
    > php typo3_convert_extension_to_namespaces.php
        
or make the script executable:

    > chmod +x typo3_convert_extension_to_namespaces.php
    
and run it

    > ./typo3_convert_extension_to_namespaces.php
    
Then you may copy it ...

    > cp typo3_convert_extension_to_namespaces.php /usr/local/bin/typo3_convert_extension_to_namespaces
    
and just run it with 
    
    > typo3_convert_extension_to_namespaces
    
## Usage
    
Just call the script it should give you hints how to use it.

## Remarks

I used this code over the years and lately I changed it to exist as a cli. It worked for me fine. But if it kills your cat, don't blame me. I warned you!

## Contribute

- Send pull requests to the repository. <https://github.com/colorcube/typo3_convert_extension_to_namespaces>
- Use the issue tracker for feedback and discussions. <https://github.com/colorcube/typo3_convert_extension_to_namespaces/issues>