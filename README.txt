-- SUMMARY --

This module generates PDF Invoice of order and sends PDF 
as an attachment to customer.

-- REQUIREMENTS --
PHP 5.3 or higher versions.
Drupal 7.x.
DOMPDF 0.8.x Library or higher: https://github.com/dompdf/dompdf/releases

-- MODULE DEPENDENCY --
This module requires the following modules:

Ubercart
Mail system
Mime Mail
libraries

-- INSTALLATION --
To install Ubercart PDF Invoice Mail:

  1. Upload the 'uc_pdf_invoice_mail' folder into your module directory and
     activate the modules.


  2. Upload dompdf library (https://github.com/dompdf/dompdf/releases) 
     into the libraries folder so that it looks like 
     'sites/all/libraries/dompdf/autoload.inc.php'.


  3. Enable the Ubercart PDF Invoice Mail module under 'Ubercart - extra'
    in the Drupal module administration page.


  4. Thats it!. Now invoice attachment will get sent along with invoice mail.
