export CC := clang
export CCFLAGS := -Wall
export TARGET := aarch64-linux-gnu
export FUSELD := lld

example-7: example-7.c
	$(CC) -MJ ./compile_commands.json --target=$(TARGET) -fuse-ld=$(FUSELD) $(CCFLAGS) $^ -o $@

clean:
	rm -f example-7
