# CKAN Contact Extension

This extension adds a contact form

**DEMO:** http://data.nhm.ac.uk/

**Settings**
```
ckanext.contact.mail_to =
ckanext.contact.mail_to_cc
ckanext.contact.recipient_name =
ckanext.contact.subject =

# email of recipients to  blacklist seperated by space. optional
ckanext.contact.blacklist =

# recaptcha v3 settings, these are optional
ckanext.contact.recaptcha_v3_key =
ckanext.contact.recaptcha_v3_secret =
ckanext.contact.recaptcha_v3_action =
```

If ckanext.contact.mail_to is not set, the form will fall back to using the CKAN setting "email_to".

**Credits:**

Borrows much of the contact form code from https://github.com/CityofSurrey/ckanext-surrey
