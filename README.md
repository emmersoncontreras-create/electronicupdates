# Actualizaciones de Factura POS

Archivos que descargan los programas instalados para actualizarse solos. No contienen datos de clientes.

- `version.json`: version vigente, huella SHA-256 del instalador y firma digital del proveedor.
- `FacturaPOS-actualizacion-*.exe`: instalador de la version vigente.

El programa solo acepta actualizaciones cuya firma verifica con la llave publica incluida en el.
