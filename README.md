# BarCodeScanner
Application to scan basic bar codes and VIN Barcodes and display as a alert, you can modify action according to you need.
You can add more bar code / QR code type by adding MetaDataType in " metadataOutput.metadataObjectTypes = [] " Part of View Controller.
Just add the type , like currently it supports 

AVMetadataObjectTypeEAN13Code,
AVMetadataObjectTypeCode39Code,
AVMetadataObjectTypeCode39Mod43Code,
AVMetadataObjectTypeQRCode
