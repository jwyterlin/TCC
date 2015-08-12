# Macros:
CPP= g++
CFLAGS= -O3 -fopenmp
OBJECTS= SampleDecoder.o samplecode.o

# Targets:
all: samplecode

samplecode: $(OBJECTS)
	$(CPP) $(CFLAGS) $(OBJECTS) -o samplecode
        
SampleDecoder.o:
	$(CPP) $(CFLAGS) -c SampleDecoder.cpp

samplecode.o:
	$(CPP) $(CFLAGS) -c samplecode.cpp

# Remove:
clean:
	rm -f sampledecode $(OBJECTS)
