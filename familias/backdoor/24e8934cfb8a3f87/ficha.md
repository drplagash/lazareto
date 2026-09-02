# 24e8934cfb8a3f87

```
sha256:        24e8934cfb8a3f8773054455916fb8ef595230bb644df38bcd6bfe98ec4f4bcc
kind:          pe
mime_type:     PE32 executable (DLL) (GUI) Intel 80386, for MS Windows, 5 sections
architecture:  x86
size_bytes:    72707
first_seen:    2026-09-02 02:32:54.267804 UTC
times_seen:    1
classification:backdoor
yara_matches:  anti_dbg, Borland_Delphi_30_, Borland_Delphi_30_additional, Borland_Delphi_DLL, Borland_Delphi_v30, Borland_Delphi_v40_v50, HasDebugData, HasOverlay, HasRichSignature, IsDLL, IsPE32, IsWindowsGUI, maldoc_find_kernel32_base_method_1, Microsoft_Visual_Cpp_v50v60_MFC, network_dropper, SEH_Init, SEH_Save, win_files_operation
```

**Payload de origen:** sin vinculo conocido (captura via explotacion de protocolo o sin sesion de shell asociada)

## VirusTotal

- **Veredicto: MALICIOSO CONFIRMADO** (56/71 motores)
- Etiqueta sugerida: trojan.downldr/usblga26
- Nombre conocido: 24e8934cfb8a3f8773054455916fb8ef595230bb644df38bcd6bfe98ec4f4bcc.pe
- Tipo (VT): Win32 DLL

## Wallet

- No se pudo extraer una wallet en texto plano de esta muestra (probablemente se configura en runtime desde el C2, no esta hardcodeada).

## Archivo

`muestra.zip` - password: `infected`
