Author: Maximilian Graml

Mail:   maximilian.graml(at)ur.de

OrcID:  0000-0002-4279-8511


Timings are extracted from the final timetable for the "gw"-module entry in the TOTAL TIME MAXIMUM column, e.g. 13852.29 for
                gw                                   1  5.0     0.00     0.00 13851.15 13852.29
     
The timing for 3c integral in Subfigure e is extracted from the TOTAL TIME MAXIMUM column for the "compute_3c_integrals"-module

Licenses:       None/?

Version:        2025.2 (Dev Version) - git:3ae2ba4

Dependencies:   CP2K| cp2kflags: omp libint fftw3 libxc libgrpp elpa parallel scalapack mpi_f08

                CP2K|             cosma xsmm plumed2 spglib sirius libvori libbqb libvdwxc hdf5
                
                ---> cf. Make file


System:         Otus@PC2 (2x AMD EPYC 9655 96-Core Processor per Node; normal and largemem queues)


Output of -v:   SIRIUS 7.7.0, git hash: https://api.github.com/repos/electronic-structure/SIRIUS/git/ref/tags/v7.7.0
                CP2K version 2025.2 (Development Version)
                Source code revision git:3ae2ba4
                cp2kflags: omp libint fftw3 libxc libgrpp elpa parallel scalapack mpi_f08 cosma xsmm plumed2 spglib sirius libvori libbqb libvdwxc hdf5
                compiler: GCC version 14.2.0
                compiler options:
                -cpp -I /opt/software/pc2/EB-SW/software/OpenMPI/5.0.7-GCC-14.2.0/in
                clude -I /opt/software/pc2/EB-SW/software/OpenBLAS/0.3.29-GCC-14.2.0
                /include -I /opt/software/pc2/EB-SW/software/FFTW.MPI/3.3.10-gompi-2
                025a/include -I /opt/software/pc2/EB-SW/software/CP2K/2025.2-foss-20
                25a-gcc-openmpi-aocl/tools/toolchain/install/libint-v2.6.0-cp2k-lmax
                -7/include -I /opt/software/pc2/EB-SW/software/CP2K/2025.2-foss-2025
                a-gcc-openmpi-aocl/tools/toolchain/install/libxc-7.0.0/include -I /o
                pt/software/pc2/EB-SW/software/CP2K/2025.2-foss-2025a-gcc-openmpi-ao
                cl/tools/toolchain/install/libxsmm-e0c4a2389afba36c453233ad7de07bd92
                c715bec/include -I /opt/software/pc2/EB-SW/software/CP2K/2025.2-foss
                -2025a-gcc-openmpi-aocl/tools/toolchain/install/COSMA-2.7.0/include 
                -I /opt/software/pc2/EB-SW/software/CP2K/2025.2-foss-2025a-gcc-openm
                pi-aocl/tools/toolchain/install/elpa-2024.05.001/cpu/include/elpa_op
                enmp-2024.05.001/modules -I /opt/software/pc2/EB-SW/software/CP2K/20
                25.2-foss-2025a-gcc-openmpi-aocl/tools/toolchain/install/elpa-2024.0
                5.001/cpu/include/elpa_openmp-2024.05.001/elpa -I /opt/software/pc2/
                EB-SW/software/CP2K/2025.2-foss-2025a-gcc-openmpi-aocl/tools/toolcha
                in/install/hdf5-1.14.6/include -I /opt/software/pc2/EB-SW/software/C
                P2K/2025.2-foss-2025a-gcc-openmpi-aocl/tools/toolchain/install/libvd
                wxc-0.4.0/include -I /opt/software/pc2/EB-SW/software/CP2K/2025.2-fo
                ss-2025a-gcc-openmpi-aocl/tools/toolchain/install/spglib-2.5.0/inclu
                de -I /opt/software/pc2/EB-SW/software/CP2K/2025.2-foss-2025a-gcc-op
                enmpi-aocl/tools/toolchain/install/pugixml-1.15/include -I /opt/soft
                ware/pc2/EB-SW/software/CP2K/2025.2-foss-2025a-gcc-openmpi-aocl/tool
                s/toolchain/install/SpFFT-1.1.1/include -I /opt/software/pc2/EB-SW/s
                oftware/CP2K/2025.2-foss-2025a-gcc-openmpi-aocl/tools/toolchain/inst
                all/SpLA-1.6.1/include/spla -I /opt/software/pc2/EB-SW/software/CP2K
                /2025.2-foss-2025a-gcc-openmpi-aocl/tools/toolchain/install/sirius-7
                .7.0/include/sirius -I /opt/software/pc2/EB-SW/software/CP2K/2025.2-
                foss-2025a-gcc-openmpi-aocl/tools/toolchain/install/dbcsr-2.8.0/incl
                ude -I /pc2/users/e/eprop2d2/cp2k_dev/src/start/ -I /pc2/users/e/epr
                op2d2/cp2k_dev/obj/local_otus_dev/psmp/exts/dbcsr -I /opt/software/p
                c2/EB-SW/software/OpenMPI/5.0.7-GCC-14.2.0/include -I /opt/software/
                pc2/EB-SW/software/OpenMPI/5.0.7-GCC-14.2.0/lib -D_REENTRANT -D __LI
                BXSMM -D __parallel -D __MPI_F08 -D __FFTW3 -D __LIBINT -D __LIBXC -
                D __LIBGRPP -D __parallel -D __COSMA -D __ELPA -D __GSL -D __PLUMED2
                    -D __HDF5 -D __LIBVDWXC -D __SPGLIB -D __LIBVORI -D __SPFFT -D __SP
                LA -D __SIRIUS -D __DBCSR -D __COMPILE_ARCH="local_otus_dev" -D __CO
                MPILE_DATE="Thu Jan 22 03:37:42 PM CET 2026" -D __COMPILE_HOST="logi
                n1" -D __COMPILE_REVISION="git:3ae2ba4" -D __SHORT_FILE__="start/cp2
                k.F" -march=znver5 -mmmx -mpopcnt -msse -msse2 -msse3 -mssse3 -msse4
                .1 -msse4.2 -mavx -mavx2 -msse4a -mno-fma4 -mno-xop -mfma -mavx512f 
                -mbmi -mbmi2 -maes -mpclmul -mavx512vl -mavx512bw -mavx512dq -mavx51
                2cd -mavx512vbmi -mavx512ifma -mavx512vpopcntdq -mavx512vbmi2 -mgfni
                    -mvpclmulqdq -mavx512vnni -mavx512bitalg -mavx512bf16 -mavx512vp2in
                tersect -mno-3dnow -madx -mabm -mno-cldemote -mclflushopt -mclwb -mc
                lzero -mcx16 -mno-enqcmd -mf16c -mfsgsbase -mfxsr -mno-hle -msahf -m
                no-lwp -mlzcnt -mmovbe -mmovdir64b -mmovdiri -mmwaitx -mno-pconfig -
                mpku -mprfchw -mno-ptwrite -mrdpid -mrdrnd -mrdseed -mno-rtm -mno-se
                rialize -mno-sgx -msha -mshstk -mno-tbm -mno-tsxldtrk -mvaes -mno-wa
                itpkg -mwbnoinvd -mxsave -mxsavec -mxsaveopt -mxsaves -mno-amx-tile 
                -mno-amx-int8 -mno-amx-bf16 -mno-uintr -mno-hreset -mno-kl -mno-wide
                kl -mavxvnni -mno-avx512fp16 -mno-avxifma -mno-avxvnniint8 -mno-avxn
                econvert -mno-cmpccxadd -mno-amx-fp16 -mno-prefetchi -mno-raoint -mn
                o-amx-complex -mno-avxvnniint16 -mno-sm3 -mno-sha512 -mno-sm4 -mno-a
                pxf -mno-usermsr --param=l1-cache-size=48 --param=l1-cache-line-size
                =64 --param=l2-cache-size=1024 -mtune=znver5 -g -O3 -std=f2008 -fno-
                omit-frame-pointer -fopenmp -funroll-loops -fbacktrace -ffree-form -
                fimplicit-none -fallow-argument-mismatch -fpre-include=/usr/include/
                finclude/math-vector-fortran.h
