

# Présentation / Overview

Avec `benalgodev/EDI`, vous pouvez **lire et écrire des fichiers XML** contenant des données de factures électroniques selon les profils : **Minimum, Basic, EN16931, Extended et XRechnung**.

De plus, il est possible **d’attacher les données XML à un fichier PDF existant**, par exemple un PDF généré à partir d’un système ERP.

Si vous disposez à la fois d’un fichier XML (ou d’une chaîne XML) et d’un fichier PDF (ou d’un PDF sous forme de chaîne), vous pouvez créer un **fichier PDF conforme avec pièce jointe** à l’aide de la classe `ZugferdDocumentPdfMerger`.

**L’avantage de cette bibliothèque est que vous n’avez pas à vous soucier de savoir si un élément XML particulier existe dans un profil donné — le même code peut être utilisé pour tous les profils pris en charge.**

---

With `benalgodev/EDI`, you can **read and write XML files** containing electronic invoice data according to the following profiles: **Minimum, Basic, EN16931, Extended, and XRechnung**.

Additionally, it is possible to **attach the XML data to an existing PDF file**, for example a PDF generated from an ERP system.

If you have both an XML file (or XML string) and a PDF file (or PDF as a string), you can create a **compliant PDF file with attachment** using the `ZugferdDocumentPdfMerger` class.

**The advantage of this library is that you don’t have to worry about whether a specific XML element exists in a given profile — the same code can be used for all supported profiles.**

---

# Profils pris en charge / Supported Profiles

* EN16931 Minimum
* EN16931 Basic
* EN16931 Basic WL
* EN16931 Comfort
* EN16931 Extended
* EN16931 XRechnung 1.x
* EN16931 XRechnung 2.x
* EN16931 XRechnung 3.x

> ⚠️ **Important / Important**
> Ce package ne prend en charge que la **syntaxe CII** — pas la syntaxe **UBL**.
> This package only supports **CII syntax** — UBL syntax is not supported.

---

# Informations supplémentaires / Further Information

* [ZUGFeRD](https://de.wikipedia.org/wiki/ZUGFeRD) (allemand / German)
* [XRechnung](https://de.wikipedia.org/wiki/XRechnung) (allemand / German)
* [Factur-X](http://fnfe-mpe.org/factur-x/factur-x_en) (français / French)

---

# Dépendances / Dependencies

Ce package utilise les bibliothèques suivantes :
This package uses the following libraries:

* [JMS Serializer](http://jmsyst.com/libs/serializer)
* [Xsd2Php](https://github.com/goetas-webservices/xsd2php)
* [FPDF](https://github.com/Setasign/FPDF)
* [FPDI](https://github.com/Setasign/FPDI)

---

# Ressources / Resources

* [Documentation officielle (archive des versions)](https://www.ferd-net.de/ueber-uns/ressourcen-1/veroeffentlichungen)
* [Official documentation (version archive)](https://www.ferd-net.de/ueber-uns/ressourcen-1/veroeffentlichungen)

