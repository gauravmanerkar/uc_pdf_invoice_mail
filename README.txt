-- SUMMARY --
This module generates PDF Invoice of order and sends PDF 
as an attachment to customer.

-- REQUIREMENTS --
Drupal 8.x
DOMPDF Library (Install using composer: Command - composer require dompdf/dompdf)

-- MODULE DEPENDENCY --
This module requires the following modules:
- Ubercart

-- INSTALLATION --
To install Ubercart PDF Invoice Mail:
  1. Upload the 'uc_pdf_invoice_mail' folder into your module directory and
     activate the modules.
  2. Make sure Dompdf library is installed using composer (Command - composer require dompdf/dompdf).
  3. Enable the Ubercart PDF Invoice Mail module under 'Ubercart - extra'
    in the Drupal module administration page.
  4. Thats it!. Now invoice attachment will get sent along with invoice mail.
