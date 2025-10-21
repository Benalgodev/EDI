
Présentation
Avec benalgodev/EDI, vous pouvez lire et écrire des fichiers XML contenant des données de factures électroniques selon les profils Minimum, Basic, EN16931, Extended et XRechnung.
De plus, il est possible d’attacher les données XML à un fichier PDF existant, par exemple un PDF généré à partir d’un système ERP.
Si vous disposez à la fois d’un fichier XML (ou d’une chaîne XML) et d’un fichier PDF (ou d’un PDF sous forme de chaîne), vous pouvez créer un fichier PDF conforme avec pièce jointe à l’aide de la classe ZugferdDocumentPdfMerger.
L’avantage de cette bibliothèque est que vous n’avez pas à vous soucier de savoir si un élément XML particulier existe dans un profil donné — le même code peut être utilisé pour tous les profils pris en charge.
Profils pris en charge
    • EN16931 Minimum
    • EN16931 Basic
    • EN16931 Basic WL
    • EN16931 Comfort
    • EN16931 Extended
    • EN16931 XRechnung 1.x
    • EN16931 XRechnung 2.x
    • EN16931 XRechnung 3.x
[!IMPORTANT]
Ce package ne prend en charge que la syntaxe CII — pas la syntaxe UBL.
Informations supplémentaires
    • ZUGFeRD (allemand)
    • XRechnung (allemand)
    • Factur-X (français)
Dépendances
Ce package utilise les bibliothèques suivantes :
    • JMS Serializer
    • Xsd2Php
    • FPDF
    • FPDI
Ressources
    • Documentation officielle (archive des versions)
Guide
Pour une explication détaillée, vous pouvez consulter les exemples du package, la documentation jointe à chaque version ou notre wiki.
Les sections suivantes sont documentées dans notre Wiki :
    • Installation
    • Configuration
    • Lire un fichier XML
    • Lire un fichier PDF avec un fichier XML joint
    • Écrire un fichier XML
    • Écrire un fichier PDF avec un fichier XML joint
    • Fusionner un PDF et un XML existants
    • Validation