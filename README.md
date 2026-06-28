# MogiBiz

 Aplikasi ini adalah simulator bisnis interaktif (What-If Analysis) yang berjalan 100% offline.

## Prasyarat

1. Microsoft C++ Build Tools (Compile Rust di Windows)
    - Download: https://visualstudio.microsoft.com/visual-cpp-build-tools/
    - Saat installer jalan, centang: "Desktop development with C++" → Install

3. Rust (Tauri)
    - Download & jalankan rustup-init.exe dari: https://www.rust-lang.org/tools/install
    - Pilih opsi default (1).
    - Restart terminal setelah selesai.
    - ```
      rustc --version   # verifikasi

4. Node.js LTS (Scaffolding Project)
    - Download: https://nodejs.org/ (versi LTS, mis. 20.x)
    - ```
      node -v
    - ```
      npm -v
### Install

1. Clone Repositori
   ``` 
   git clone https://github.com/farizsidki/mogibiz.git
   
2. Pindah Repositori
   ``` 
   cd mogibiz
   
3. Build
   ``` 
   npm run tauri build
4. Output:
   ```
   src-tauri\target\release\bundle\nsis\MogiBiz_1.0.0_x64-setup.exe
   ```
5. Setiap update file
   ```
   npm run tauri build
7. Preview cepat tanpa build full installer
   ```
   npm run tauri dev
