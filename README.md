# Mbiz_IWantMySymlinksBack

## The story...

Magento decided to disallow symlinks in the patch SUPEE-9767. For people like us who works with composer, symlinks are 
a good system to dynamically add modules.  

## Action !

So this module re-activate the configuration in backend :

`System > Configuration > Advanced > Developer > Template Settings`

It also removes the warning block which is not necessary.

## Profit !

You can allow or disallow symlinks like before \o/