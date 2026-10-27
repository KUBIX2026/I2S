# Periférico `perip_i2s`

Transmisor I2S con FIFO, conectado al bus CSR del SoC en `0x0047_0000`. La especificación completa (registros, errores, parámetros y criterios de aceptación) está en el [README principal](../../README.md).

| Directorio | Contenido |
|---|---|
| [`diagramas/`](diagramas/) | Diagramas de flujo, bloques y estados del periférico |
| [`rtl/`](rtl/) | Módulos Verilog, testbenches, archivos `.gtkw`, `Makefile` y `.svg` |
| [`firmware/`](firmware/) | Driver en C (`i2s.h`, `i2s.c`) |
