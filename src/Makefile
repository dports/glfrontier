# src/Makefile
OBJS = $(SOURCES:.c=.o)

all: frontier.exe

frontier.exe: $(OBJS)
	$(CC) $(CFLAGS) -o $@ ${^} $(LIBS)

%.o: %.c
	$(CC) $(CFLAGS) -c -o $@ $<

clean:
	rm -f $(OBJS) frontier.exe