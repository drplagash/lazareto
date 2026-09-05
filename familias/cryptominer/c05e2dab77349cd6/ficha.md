# c05e2dab77349cd6

```
sha256:        c05e2dab77349cd639aa837e7e121710b8a0718d8fc93fb4cc6458ae90e5c597
kind:          pe
mime_type:     PE32 executable (DLL) (GUI) Intel 80386, for MS Windows, 5 sections
architecture:  x86
size_bytes:    5267459
first_seen:    2026-09-04 23:05:57.495784 UTC
times_seen:    1
classification:cryptominer
yara_matches:  anti_dbg, Armadillo_v1xx_v2xx, Armadillo_v1xx_v2xx_additional, Armadillov1xxv2xx, CRC32_poly_Constant, CRC32_table, HasOverlay, HasRichSignature, IsDLL, IsPE32, IsWindowsGUI, maldoc_getEIP_method_1, maldoc_indirect_function_call_3, Microsoft_Visual_Cpp_60, Microsoft_Visual_Cpp_60_DLL, Microsoft_Visual_Cpp_60_DLL_additional, Microsoft_Visual_Cpp_60_DLL_Debug, Microsoft_Visual_Cpp_v50v60_MFC, Microsoft_Visual_Cpp_v60_DLL, Microsoft_Visual_Cpp_v70_DLL, MS17_010_WanaCry_worm, RijnDael_AES, RijnDael_AES_CHAR, SEH_Init, Str_Win32_Internet_API, Str_Win32_Wininet_Library, Str_Win32_Winsock2_Library, Wanna_Cry_Ransomware_Generic, WannaCry_Ransomware, wannacry_static_ransom, WannaDecryptor, win_files_operation, win_registry, worm_ms17_010
```

**Payload de origen:** sin vinculo conocido (captura via explotacion de protocolo o sin sesion de shell asociada)

## VirusTotal

- **Veredicto: MALICIOSO CONFIRMADO** (66/75 motores)
- Etiqueta sugerida: trojan.wanna/wannacry
- Nombre conocido: c05e2dab77349cd639aa837e7e121710b8a0718d8fc93fb4cc6458ae90e5c597.pe
- Tipo (VT): Win32 DLL

## Wallet

- No se pudo extraer una wallet en texto plano de esta muestra (probablemente se configura en runtime desde el C2, no esta hardcodeada).

## Archivo

`muestra.zip` - password: `infected`
