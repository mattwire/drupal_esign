Esign module

About
-----
This module allows for integration of Signature Pad, an electronic-signing
script, into Drupal for both nodes (content) and the Field API (FAPI).


Requirements
-----------
- Libraries Module
  Link: https://www.drupal.org/project/libraries
- Signature Pad library
  Link: https://github.com/szimek/signature_pad


Installation instructions
-------------------------
1. Download and extract the Signature Pad library into the libraries directory
   (usually "sites/all/libraries").
   Link: https://github.com/szimek/signature_pad

2. Download and extract the Esign (this) module into the modules directory
   (usually "sites/all/modules").
   Link: http://drupal.org/project/esign

3. Go to "Administer" -> "Modules" and enable the module.


Upgrade instructions
--------------------
None yet!  

Configuring the field
---------------------
For content, you can change the options within the field settings.

For FAPI, you can change the field options by setting the '#esign_options'
parameter, and using the following keys in an associative array:
- dotSize (default: 1)
- minWidth (default: 0.5)
- maxWidth (default: 2.5)
- backgroundColor (default: 'rgba(0,0,0,0)')
- penColor (default: 'rgba(0,0,0,1)')
- velocityFilterWeight (default: 0.7)


Using the output
----------------
In FAPI, the output of the field is a BASE64 encoded PNG.


Support requests
----------------
You can request support here: http://drupal.org/project/issues/esign


How to help?
------------
Glad you asked that :)

- Help find bugs!
- Suggest new features!
- Test the beta versions!
- Translate the UI into your language!
