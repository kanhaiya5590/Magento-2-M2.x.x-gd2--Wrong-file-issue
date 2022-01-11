# Magento 2 Gd2 Wrong file
In PatchApplier.php line 170:  Unable to apply data patch `Magento\Theme\Setup\Patch\Data\RegisterThemes` for module `Magento_Theme`. Original exception message: Wrong file   

***In Gd2.php line 72: Wrong file***

![Error Screenshot](screenshot.png)

# To fix apply shared patch

`git apply` [kanhaiya5590-M2.x.x-gd2-image-issue.patch](kanhaiya5590-M2.x.x-gd2-image-issue.patch)

 ***Not: considering we download the patch file on root of the project directory or update path in command accordingly, when executing command***
 
 
 # To revert the applied patch
 `git apply -R` [kanhaiya5590-M2.x.x-gd2-image-issue.patch](kanhaiya5590-M2.x.x-gd2-image-issue.patch)
