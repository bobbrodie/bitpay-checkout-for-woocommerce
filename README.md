BitPay Checkout for Woocommerce
===============================

This plugin allows stores using the WooCommerce shopping cart system to accept cryptocurrency payments via the BitPay gateway. It only takes a few minutes to configure.

# Requirements

This plugin requires the following:

* [Woocommerce](https://wordpress.org/plugins/woocommerce/).
* A BitPay merchant account ([Test](http://test.bitpay.com) and [Production](http://www.bitpay.com))

# Installation

Install the plugin via the [Wordpress Plugin Manager](https://wordpress.org/plugins/bitpay-checkout-for-woocommerce/#installation).

### When Installing From the Downloadable Archive

Visit the [Releases](https://github.com/bitpay/bitpay-checkout-for-woocommerce/releases) page of this repository and download the latest version. Once this is done, you can just go to Wordpress's Adminstration Panels > Plugins > Add New > Upload Plugin, select the downloaded archive and click Install Now. After the plugin is installed, click on Activate.

**WARNING:** 
* It is good practice to backup your database before installing plugins. Please make sure you create backups.
* If you were using a previous version of this plugin, this version (3.0) was completely rewritten to improve the user experience and the security. You will need to renew the configuration of the plugin (fetch a new API token from the BitPay merchant dashboard).

## Support

**BitPay Support:**

* Last Cart Version Tested: Wordpress 6.2.2
* [GitHub Issues](https://github.com/bitpay/bitpay-checkout-for-woocommerce/issues)
* [Support](https://support.bitpay.com/hc/en-us)

## Troubleshooting

The latest version of this plugin can always be downloaded from the official BitPay repository located here: https://github.com/bitpay/bitpay-checkout-for-woocommerce

* This plugin requires PHP 8.0 or higher to function correctly. Contact your webhosting provider or server administrator if you are unsure which version is installed on your web server.
* Ensure a valid SSL certificate is installed on your server. Also ensure your root CA cert is updated. If your CA cert is not current, you will see curl SSL verification errors.
* Verify that your web server is not blocking POSTs from servers it may not recognize. Double check this on your firewall as well, if one is being used.
* Check the system error log file (usually the web server error log) for any errors during BitPay payment attempts. If you contact BitPay support, they will ask to see the log file to help diagnose the problem.
* Check the version of this plugin against the official plugin repository to ensure you are using the latest version. Your issue might have been addressed in a newer version!

**NOTE:** When contacting support it will help us if you provide:

* WordPress and WooCommerce Version
* PHP Version
* Other plugins you have installed
* Configuration settings for the plugin (Most merchants take screen grabs)
* Any log files that will help
* Web server error logs
* Screen grabs of error message if applicable.

## Contribute

Would you like to help with this project?  Great!  You don't have to be a developer, either.  If you've found a bug or have an idea for an improvement, please open an [issue](https://github.com/bitpay/bitpay-checkout-for-woocommerce/issues) and tell us about it.

If you *are* a developer wanting contribute an enhancement, bugfix or other patch to this project, please fork this repository and submit a pull request detailing your changes.  We review all PRs!

This open source project is released under the [MIT license](http://opensource.org/licenses/MIT) which means if you would like to use this project's code in your own project you are free to do so. Speaking of, if you have used our code in a cool new project we would like to hear about it!  Please send us an [email](mailto:sales-engineering@bitpay.com).

## License

Please refer to the [LICENSE](https://github.com/bitpay/bitpay-checkout-for-woocommerce/blob/master/LICENSE) file that came with this project.
