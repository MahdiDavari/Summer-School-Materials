CXX = icpc
CXXFLAGS = -g -Wall
CXXLIBS = -mkl

scf: scf.o diag.o mmult.o
	$(CXX) $^ $(CXXLIBS) -o $@

clean:
	rm -f *.o scf
