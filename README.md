# [[fishfin] php_ibm_db2](https://github.com/fishfin/php_ibm_db2)

> `#php_pdo_ibm` `#php_ibm_db2` `#windows-dll`

This is a megapack of Windows DLLs for [`php_pdo_ibm (v1.3.6)`](https://pecl.php.net/package/PDO_IBM) and [`php_ibm_db2 (v2.0.8)`](https://pecl.php.net/package/ibm_db2) extensions, for `PHP 5.6`, `PHP 7.0`, `PHP 7.1`, `PHP 7.2`, `PHP 7.3` and `PHP 7.4`, for `threadsafe` and `non-threadsafe` versions, for `32-bit` and `64-bit` systems (total 48 DLLs).

> I have spent over 2 weeks in:
> (1) downloading hard-to-find old Visual Studio Express/Community versions
> (2) googling and collating various pages of information on compiling
> (3) resolving C++ and makefile errors (I have zero knowledge of this)
> (4) compiling all 48 DLLs (when I needed barely 2 versions)
> with a hope that it will be useful to somebody. If it was useful to you, I'll be happy to know, please drop me an email at mailbox.fishfin@gmail.com,

### Important Disclaimer

The original sources of the respective extensions are located at the links as referenced above. The sources contain errors when compiled for PHP 7.4 (invalid declaration of a variable, and no handling of 64-bit in makefile), which have been corrected. The tweaked sources are also available for downloads along with the DLLs from this repository.

If in doubt, please use this repository: https://github.com/ibmdb/php_ibm_db2. When I compiled these DLLs, very few DLLs were available at the IBMDB repository, though there seem to be much more now. I also have some information that some of the DLLs at IBMDB repository crash with PHP FCGID (but work fine with my compilation), your mileage may vary. You can try both to see which ones work for you.