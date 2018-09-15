project(mammal)

if (NOT CMAKE_BUILD_TYPE)
    set(CMAKE_BUILD_TYPE "Release")
endif()

add_executable(mammal-sigma mammal-sigma.c mammal-sigmaf.c mammal-sigma.h)
add_executable(mult-data mult-data.c mult-dataf.c mult-data.h)
add_executable(mult-mix-lwt mult-mix-lwt.c mult-mix-lwtf.c mult-mix-lwt.h)
add_executable(charfreq charfreq.c charfreqf.c charfreq.h)
add_executable(dgpe dgpe.c dgpef.c dcdflib.c ipmpar.c cdflib.h dgpe.h aa_empirical.h)
