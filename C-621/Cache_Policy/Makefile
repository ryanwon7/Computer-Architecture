SOURCE	:= Main.c Trace.c Cache.c
CC	:= gcc
TARGET	:= Main
LINK	:= -lm

all: $(TARGET)

$(TARGET): $(SOURCE)
	$(CC) -o $(TARGET) $(SOURCE) $(LINK)

run:	$(TARGET)
	./Main 531.deepsjeng_r_llc.mem_trace
	./Main 541.leela_r_llc.mem_trace
	./Main 548.exchange2_r_llc.mem_trace

clean:
	rm -f $(TARGET)
