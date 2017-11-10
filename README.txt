/**
 * uc_pdf_invoice_mail: Generates PDF of order invoice and sends 
 * as attachment in mail to customer
 *
 * Original credits, 1.x development:
 *
 * Developed by Gaurav Manerkar
 */

This module created PDF Invoices and store orders and
sends PDF as and attachment to customers

DEPENDENCIES

There are dependencies for this module:

 DOMPDF

REQUIREMENTS
This module requires the following modules:

Libraries
Ubercart
Mail system
Mime Mail

INSTALLATION

To install Ubercart PDF Invoice Mail:

1) Download the latest release of this module .

2) Uncompress the archive in your Ubercart contrib directory:
[your Drupal root]/sites/all/modules.

3) Download the lastest stable DOMPDF(https://github.com/dompdf/dompdf/releases) 
library from github.

4) After download extract it to your sites sites/all/libraries folder 
and rename it to "dompdf".

5) Make sure libraries folder have structure 
   sites/all/libraries/dompdf/autoload.inc.php

6) Enable the Ubercart PDF Invoice Mail module under 
'Ubercart - extra' in the Drupal module administration page.

7) Thats it!. Now invoice attachment will get sent along with invoice mail.

