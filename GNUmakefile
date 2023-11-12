CFLAGS ?= -Wall
FRAMEWORKS = -framework CoreFoundation -framework IOKit

ezload: main.o
	$(CC) $(CFLAGS) $(FRAMEWORKS) -o $@ $?

%.o: %.m %.c
	$(CC) $(CFLAGS) -c -x objective-c -o $@ $?
