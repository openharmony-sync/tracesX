# Run Stream

- Updated: `2026-06-11 17:38:10 UTC`
- Status: `OK`
- Run id: `cmd_20260611_173758_compress_es2abc_xz9_1781199469`
- Kind: `control-command`
- Target: `build`
- Command id: `compress_es2abc_xz9_1781199469`
- Exit code: `0`
- Duration seconds: `10.587`
- Encoded log manifest: [run_stream_logs/cmd_20260611_173758_compress_es2abc_xz9_1781199469/manifest.json](run_stream_logs/cmd_20260611_173758_compress_es2abc_xz9_1781199469/manifest.json)
- Encoded log parts: `1`

## Reconstruct Captured Output

```bash
cat part_*.b64 | base64 -d | xz -dc > combined.log
```

## Parts

- [run_stream_logs/cmd_20260611_173758_compress_es2abc_xz9_1781199469/part_00001.b64](run_stream_logs/cmd_20260611_173758_compress_es2abc_xz9_1781199469/part_00001.b64)
