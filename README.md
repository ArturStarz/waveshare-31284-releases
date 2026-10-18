# Waveshare 31284 – wydania firmware

Pliki firmware dla płytki Waveshare 31284 (ESP32-S3-ETH-8DI-8RO-C) używane przez aktualizację z serwera.

Każde wydanie zawiera:
- `manifest.json` – wersja, opis zmian, rozmiary i sumy SHA-256 plików,
- `manifest.sig` – podpis ECDSA P-256 manifestu (płytka przyjmuje tylko podpisane wydania),
- `ws31284-<wersja>.bin`, `ws31284-tmlab-<wersja>.bin` – firmware dla wariantów.

Płytka pobiera `releases/latest/download/manifest.json`. Pliki nie zawierają haseł ani ustawień.
