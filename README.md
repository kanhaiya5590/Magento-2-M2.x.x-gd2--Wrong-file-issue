# Magento 2 Gd2 Wrong file
In PatchApplier.php line 170:  Unable to apply data patch `Magento\Theme\Setup\Patch\Data\RegisterThemes` for module `Magento_Theme`. Original exception message: Wrong file   

***In Gd2.php line 72: Wrong file***

![Error Screenshot](screenshot.png)

# To fix this issue apply shared patch, considering we downloaded and root of the project directory, then executing below command

`git apply` [kanhaiya5590-M2.x.x-gd2-image-issue.patch](kanhaiya5590-M2.x.x-gd2-image-issue.patch)
