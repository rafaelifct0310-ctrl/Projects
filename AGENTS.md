# AGENTS.md

## Proyecto

- **Nombre**: Solicitud Interna
- **Tipo**: Módulo Odoo
- **Versión**: 19.0.1.0.0
- **Categoría**: General

## Descripción

Gestión de solicitudes internas para los departamentos de:
- IT (Soporte Técnico)
- RRHH (Recursos Humanos)
- Compras (Adquisiciones)

## Dependencias

- base

## Archivos

- `models/solicitud.py` - Modelos de datos
- `views/solicitud_views.xml` - Vistas
- `views/menu_items.xml` - Menú
- `security/ir.model.access.csv` - Control de acceso
- `security/solicitud_security.xml` - Seguridad
- `data/solicitud_data.xml` - Datos iniciales

## Comandos de verificación

```bash
python -m py_compile solicitud_interna/models/solicitud.py
```

## Comandos de módulo

```bash
odoo-bin -c odoo.conf -d dbname -u solicitud_interna
```