# Diagramas del sistema

Diagramas del periférico I2S dentro de la consola KUBIX. Los diagramas internos del periférico están en [`cores/i2s/diagramas/`](../cores/i2s/diagramas/).

| Archivo | Contenido | Estado |
|---|---|---|
| `i2s_contexto.png` | Cadena de salida: DAC, amplificador y parlante (MAX98357A) | Borrador: falta mostrar CPU → bus (`cs8`, `0x470000`) → `perip_i2s` |
| `i2s_firmware.png` / `.pdf` | Lazo del driver: revisar `STATUS`, recargar la FIFO, revisar errores | Pendiente |
