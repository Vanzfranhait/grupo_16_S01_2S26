# Diario de trabajo

| Fecha | Tarea | Participantes | Decisiones | Problemas | Solución | Resultado | Evidencia |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-10-16 | Preparación de VM, disco LFS y verificación de anfitrión | Matías Jara | Segundo disco virtual de 30 GB en GPT/UEFI, LFS 12.3 systemd | `parted` reportó "partition(s) in use" sobre `/dev/sdb` (era el disco de Rocky, no el de LFS) | Verificación con `lsblk -f`; se usó `/dev/sda` (el vacío) | Anfitrión verificado sin errores | `evidencias/parte1/anfitrion.txt`, `disco-lfs.txt`, `version-check.txt` |
