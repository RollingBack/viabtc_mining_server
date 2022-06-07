TARGET  := poolbench.exe
INCS = -I ../network -I ../utils
LIBS = -L ../utils -lutils -L ../network -lnetwork -Wl,-Bstatic -lev -lhiredis -ljansson -lssl -lcrypto -Wl,-Bdynamic -ldl -lm  -lpthread -lz -lcurl
include ../makefile.inc
