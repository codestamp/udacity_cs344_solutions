############################################################################
# <summary> CMakeLists.txt for OpenCV and CUDA. </summary>
# <date>    2012-02-07          </date>
# <author>  Quan Tran Minh. edit by Johannes Kast, Michael Sarahan </author>
# <email>   quantm@unist.ac.kr  kast.jo@googlemail.com msarahan@gmail.com</email>
############################################################################

# collect source files
cmake_minimum_required(VERSION 3.8 FATAL_ERROR)
file( GLOB  hdr *.hpp *.h )
file( GLOB  cu  *.cu)
SET (HW1_files main.cpp reference_calc.cpp compare.cpp)
project(PILOT_plugin LANGUAGE C CXX CUDA)
#CUDA_ADD_EXECUTABLE(HW1 ${HW1_files} ${hdr} ${cu})
