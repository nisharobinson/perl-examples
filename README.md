# Perl Examples

## Description
Various small projects written in Perl.

### capture
This shows how to capture both stdout stderr and the exit code of
a system command using only core modules of perl.

### logger
Shows how to make a basic logger class using package. This example
mimics Log::Fast from CPAN to a degree but is not a replacement for
it obviously.

### yaml-reader
Shows how you can use only Perl Core Modules to read yaml files with
some restrictions, also a nice drop in subroutine.

### dbi-access-database
Example of how to connect to an mdb (access database) with perl.

#### Depedancies
`odbc-mdbtools (mdbtools)`, `libdbi-perl (DBI)`, `libdbd-odbc-perl (DBD::ODBC)`.

#### Notes
The `contacts.mdb` is from [DEVelopers HUT](https://www.devhut.net/) and can
be found at [MS Access Contact Database Template Sample](https://www.devhut.net/2016/09/01/ms-access-contact-database-template-sample/).

#### Output
````
$ ./dbi-access-database
$VAR1 = [
          'Contacts',
          'Contacts_EmailAddresses',
          'Contacts_PhoneNumbers',
          'lst_Cities',
          'lst_Contacts_Types',
          'lst_Countries',
          'lst_EmailAddressTypes',
          'lst_PhoneNumbersCategories',
          'lst_Provinces',
          'lst_Salutations'
        ];
````

## License
The license for this source code is extremely restrictive by default, this code is intended to be part of a portfolio for the repository owner.
