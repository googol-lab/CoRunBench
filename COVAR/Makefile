EXECUTABLE := covariance.exe
CFILES := covariance.c
include ../common/make.config
all:
	gcc -O3 ${CFILES} -o ${EXECUTABLE} -I${OPENCL_INC} -L${OPENCL_LIB} -lOpenCL -lm
clean:
	rm -f *~ *.exe
#
