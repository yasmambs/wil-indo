# wil-indo

Data wilayah Indonesia (Provinsi, Kabupaten/Kota, Kecamatan, Kelurahan/Desa) dalam format JSON.

Sumber data: [ibnux/data-indonesia](https://github.com/ibnux/data-indonesia) — disalin ke repo ini agar tidak bergantung pada repo pihak ketiga.

## Struktur data

- `provinsi.json` — daftar provinsi
- `kabupaten/[id provinsi].json` — daftar kabupaten/kota per provinsi
- `kecamatan/[id kabupaten].json` — daftar kecamatan per kabupaten/kota
- `kelurahan/[id kecamatan].json` — daftar kelurahan/desa per kecamatan

## Penggunaan

Diakses via GitHub Pages: `https://yasmambs.github.io/wil-indo/`

Contoh: `https://yasmambs.github.io/wil-indo/provinsi.json`
