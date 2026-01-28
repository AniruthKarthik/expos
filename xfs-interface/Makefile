CC = gcc
CFLAGS = -g -fcommon -std=gnu89
LDFLAGS = -lreadline

default: xfs-interface

xfs-interface: *.c *.h
	$(CC) $(CFLAGS) *.c -o xfs-interface $(LDFLAGS)

clean:
	$(RM) xfs-interface *.o disk.xfs rootfile.txt inodeusertable.txt
	$(RM) -rf xfs-interface.dSYM
