# About this Fork
This is a fork of the PHPExcel library to fix a bug in HLOOKUP. As the original library is not really maintained anymore
there won't likely be any PR's from this repo to the original.

# PHPExcel - OpenXML - Read, Write and Create spreadsheet documents in PHP - Spreadsheet engine
PHPExcel is a library written in pure PHP and providing a set of classes that allow you to write to and read from different spreadsheet file formats, like Excel (BIFF) .xls, Excel 2007 (OfficeOpenXML) .xlsx, CSV, Libre/OpenOffice Calc .ods, Gnumeric, PDF, HTML, ... This project is built around Microsoft's OpenXML standard and PHP.

Master: [![Build Status](https://travis-ci.org/PHPOffice/PHPExcel.png?branch=master)](http://travis-ci.org/PHPOffice/PHPExcel)

Develop: [![Build Status](https://travis-ci.org/PHPOffice/PHPExcel.png?branch=develop)](http://travis-ci.org/PHPOffice/PHPExcel)

## File Formats supported

### Reading
 * BIFF 5-8 (.xls) Excel 95 and above
 * Office Open XML (.xlsx) Excel 2007 and above
 * SpreadsheetML (.xml) Excel 2003
 * Open Document Format/OASIS (.ods)
 * Gnumeric
 * HTML
 * SYLK
 * CSV

### Writing
 * BIFF 8 (.xls) Excel 95 and above
 * Office Open XML (.xlsx) Excel 2007 and above
 * HTML
 * CSV
 * PDF (using either the tcPDF, DomPDF or mPDF libraries, which need to be installed separately)


## Requirements
 * PHP version 5.2.0 or higher
 * PHP extension php_zip enabled (required if you need PHPExcel to handle .xlsx .ods or .gnumeric files)
 * PHP extension php_xml enabled
 * PHP extension php_gd2 enabled (optional, but required for exact column width autocalculation)


## Want to contribute?

If you would like to contribute, here are some notes and guidlines:
 - All development happens on the develop branch, so it is always the most up-to-date
 - The master branch only contains tagged releases
 - If you are going to be submitting a pull request, please branch from develop, and submit your pull request back to the develop branch
 - [Helpful article about forking](https://help.github.com/articles/fork-a-repo/ "")
 - [Helpful article about pull requests](https://help.github.com/articles/using-pull-requests/ "")


## License
PHPExcel is licensed under [LGPL (GNU LESSER GENERAL PUBLIC LICENSE)](https://github.com/PHPOffice/PHPExcel/blob/master/license.md)
