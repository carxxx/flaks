# SAMC HUD — Square 1:1 Edition

Versi alternatif yang dibuat ulang dari nol untuk FiveM.

### Perubahan utama
- Rasio HUD **1:1 / persegi** (360 × 360 px).
- Background halaman benar-benar transparan agar tidak muncul kotak hitam NUI.
- Tidak ada 4 tombol header di kanan atas; HUD tidak membutuhkan cursor/F8 untuk klik apa pun.
- Layout baru: speed utama + power/vehicle cards + RPM rail + status strip.
- Kontrak telemetry `window.postMessage` tetap didukung.
- `peer.js` tetap disertakan agar kompatibel dengan sistem sync versi sebelumnya.
- Preview browser: buka `index.html?demo=1`.

### Payload telemetry yang didukung
`speed`, `speedUnit`/`unit`, `rpm`, `fuel`, `health`, `gear`, `engine`, `headlights`, `leftIndicator`/`left`, `rightIndicator`/`right`, `seatbelt`/`seatbeltFastened`, `odometer`, dan `visible`.
