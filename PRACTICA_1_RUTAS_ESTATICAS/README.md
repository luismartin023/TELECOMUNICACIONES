# Práctica 1: Rutas estáticas en cadena (4 VMs)

**Autor:** Luis Martín Peña Mejía · Matrícula 2023-4341 · INF-021

Red de tres sedes conectadas en cadena (R1–R2–R3) con direccionamiento IPv4
estático y rutas estáticas, 4 máquinas virtuales Windows como terminales,
una ACL extendida en R2 y diagnóstico de una falla provocada en la tabla
de enrutamiento.

## Contenido

- `CONFIGS/` — salida real de `show running-config` en R1, R2, R3, SW1, SW2 y SW3
- `GNS3/` — proyecto portable `Practica_Estatico_PenaMejia_2023-4341.gns3project`
- `INFORME/` — PDF del informe

## Notas

- Los nodos VMware del proyecto son clones enlazados de una VM base Windows
  local (`W10-Tiny-Base`), por lo que sus discos no viajan en el `.gns3project`.
- Interfaces FastEthernet en lugar de GigabitEthernet: nomenclatura real de la
  imagen Cisco 3725 usada en la emulación.
