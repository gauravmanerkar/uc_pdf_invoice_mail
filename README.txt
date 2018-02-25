-- INTRODUCTION --

This module generates PDF Invoice of order and sends PDF as an 
attachment to customer.


-- REQUIREMENTS --

* DOMPDF 0.8.x Library or higher: https://github.com/dompdf/dompdf/releases

* Ubercart

* libraries


-- INSTALLATION --

* Download the latest release of this module.

* Upload the 'uc_pdf_invoice_mail' folder into your module directory and
  activate the modules.

* Upload dompdf library (https://github.com/dompdf/dompdf/releases) 
  into the libraries folder so that it looks like 
 'sites/all/libraries/dompdf/autoload.inc.php'

* Enable the Ubercart PDF Invoice Mail module under 'Ubercart - extra'
  in the Drupal module administration page.

* Thats it!. Now invoice attachment will get sent along with invoice mail.


-- CONFIGURATION --

None.
