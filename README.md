# Vale test

This order makes OpenShiftAsciiDoc, raw-scoped rules work. 

````
BasedOnStyles = RedHat, AsciiDoc, OpenShiftAsciiDoc

Vocab = OpenShiftDocs
````

This order makes the Vocab work but not OpenShiftAsciiDoc raw-scoped rules.

````
Vocab = OpenShiftDocs

BasedOnStyles = RedHat, AsciiDoc, OpenShiftAsciiDoc
````
