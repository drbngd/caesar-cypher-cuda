NVCCFLAGS	:=
NVCC		:= nvcc


all: cypher particle

cypher: cypher.cu util.h
	$(NVCC) -o cypher cypher.cu $(NVCCFLAGS)

particle: particle.cu util.h
	$(NVCC) -o particle particle.cu $(NVCCFLAGS)


clean:
	rm -rf cypher particle
