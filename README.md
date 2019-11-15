

## If you don't have the /.dotnet volume defined, you get the following error:

Listing 'HTTPS' certificates on 'CurrentUser\My'.

'0' found matching the criteria.
SUBJECT - THUMBPRINT - NOT BEFORE - EXPIRES - HAS PRIVATE KEY
Checking certificates for validity.
Listing valid certificates
'0' found matching the criteria.
SUBJECT - THUMBPRINT - NOT BEFORE - EXPIRES - HAS PRIVATE KEY
Listing invalid certificates
'0' found matching the criteria.
SUBJECT - THUMBPRINT - NOT BEFORE - EXPIRES - HAS PRIVATE KEY
Listing 'HTTPS' certificates on 'LocalMachine\My'.
Filtering found certificates to those with a subject equal to 'CN=localhost'
'0' found matching the criteria.
SUBJECT - THUMBPRINT - NOT BEFORE - EXPIRES - HAS PRIVATE KEY
Listing certificates excluded from consideration.
'0' found matching the criteria.
SUBJECT - THUMBPRINT - NOT BEFORE - EXPIRES - HAS PRIVATE KEY
No valid certificates present on this machine. Trying to create one.
Saving the certificate into the certificate store.
Error saving the certificate in the certificate store 'CurrentUser\My'.
Exception message: The X509 certificate could not be added to the store.
Exception message: Access to the path '/.dotnet/corefx/cryptography/x509stores/my' is denied.
Exception message: Permission denied
There was an error saving the HTTPS developer certificate to the current user personal certificate store.