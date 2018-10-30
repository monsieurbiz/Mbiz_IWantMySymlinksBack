# I Want My Symlinks Back

## The story...

Magento decided to disallow symlinks in the patch SUPEE-9767. For people like us who works with composer, symlinks are 
a good system to dynamically add modules.

## Installation

Easy poppy: `composer require monsieurbiz/mbiz_iwantmysymlinksback=dev-master`

## Action!

So this module re-activate the configuration in backend:

`System > Configuration > Advanced > Developer > Template Settings`

It also removes the warning block which is not necessary anymore.

## Profit!

You can allow or disallow symlinks like before 🎉.

## Contribute

Please feel free to open new Pull Requests.

## License

This source code is under the MIT License.

## Authors

Thanks to Magento for removing a well used feature.

This project is maintained by Monsieur Biz.

You can find the list of [all contributors on github](https://github.com/monsieurbiz/Mbiz_IWantMySymlinksBack/graphs/contributors).
