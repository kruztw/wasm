all:
	emcc simple.c -Os -s WASM=1 -s SIDE_MODULE=1 -s EXPORTED_FUNCTIONS='["add"]' -o simple.wasm
run:
	emrun --no_browser --port 8080 .
clean:
	- rm simple.wasm
