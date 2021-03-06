CHANGELOG
=========

next
----

* Statically depend on phonenumbers
  Previously the phonenumberslight dependency was used dynamically in setup.py
  if it already was installed, causing problems with building wheels and
  with pipenv.


2.0.0 (2018-01-04)
------------------

* Add Django 2.0 support
* Drop Support for Django<1.11
* Translations: Swedish


1.3.0 (2017-04-15)
------------------

* Add rest_framework Serializer
* Hashable phonenumber object
* Various bugfixes and improvements


1.2.0 (2017-03-17)
------------------

* Django 1.10 support
* Bugfixes and cleanup
* Translations: Brazilian Portuguese, Spanish, Norwegian, Dutch, Azerbaijani, Turkish and French


1.1.0 (2016-03-30)
------------------

* Django 1.9 support
* README updated and links fixed
* support for HTML5.0 tel input type added
* locale files are now included
* new translations: Danish, Esperanto, Polish, all translations reformatted, Russian translation expanded
* PhoneNumberField.get_prep_value changed to enable setting null=True
* new widget added: PhoneNumberInternationalFallbackWidget
* new backward compatible requirement phonenumberslite instead of phonenumbers
* lots of tests
* dropped support for PHONENUMER_DEFAULT_REGION setting with typo
