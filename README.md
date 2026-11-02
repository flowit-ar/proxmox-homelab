# Proxmox Homelab

Laboratorio documentado para practicar virtualización, segmentación de red, backup y recuperación con Proxmox VE.

## Objetivo

Mantener una referencia reproducible de decisiones de diseño, procedimientos operativos y validaciones, sin incluir configuraciones de producción.

## Alcance

- Hosts Proxmox VE y administración de máquinas virtuales.
- Separación lógica de redes de administración, servicios y laboratorio.
- Estrategia de backup, verificación de restauraciones y documentación de cambios.
- Pruebas de disponibilidad y recuperación ante fallas controladas.

## Estructura sugerida

```text
proxmox-homelab/
├── docs/
│   ├── architecture.md
│   ├── backup-and-restore.md
│   └── operational-checklist.md
├── diagrams/
├── scripts/
└── README.md
```

## Principios operativos

1. Documentar cada cambio antes de aplicarlo.
2. Probar restauraciones regularmente; un backup no validado no es un backup confiable.
3. Usar nombres genéricos y valores de ejemplo para redes, IPs, usuarios y storage.
4. No publicar tokens, claves privadas, inventario real ni accesos remotos.

## Próximos entregables

- Diagrama lógico sanitizado.
- Checklist de alta de VM.
- Procedimiento de backup y prueba de restore.
- Scripts genéricos de inventario y control de estado.
