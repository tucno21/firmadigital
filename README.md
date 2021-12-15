# FIRMA DIGITAL DE XML

```
composer require catuva/firmadigital
```

```php
$objFirma = new Signature();
$flg_firma = 0; //posicion del nodo donde se firma en el XML
$ruta_archivo_xml = '../xml/b001-2.xml';
$ruta_firma = '../certificado/certificado.pfx';
$pass_firma = 'aaaaaaa'; //contraseña del certificado
$objFirma->signature_xml($flg_firma, $ruta_archivo_xml, $ruta_firma, $pass_firma);
```

para firmar archivos xml UBL2.1 facturacion electronica Perú

#CREDITOS: https://github.com/robrichards/xmlseclibs