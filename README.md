# คำสั่งคอมไพล์ hello.c เป็น wasm

clang-22 --target=wasm32 --no-standard-libraries -Wl,--export-all -Wl,--no-entry -o hello.wasm hello.c
