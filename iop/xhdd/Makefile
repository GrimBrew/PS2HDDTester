IOP_BIN = xhdd.irx
IOP_OBJS = xhdd.o xatad.o imports.o

IOP_INCS += -I../../common -I../atad/include

all: $(IOP_BIN)

clean:
	rm -r -f $(IOP_BIN) $(IOP_OBJS) $(IOP_OBJS_DIR) $(IOP_BIN_DIR) $(IOP_LIB_DIR)

include $(PS2SDK)/Defs.make
include $(PS2SDK)/samples/Makefile.iopglobal
