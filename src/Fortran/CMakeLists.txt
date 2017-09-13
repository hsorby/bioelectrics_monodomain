
add_executable(monodomain_2d_f monodomain.F90)

target_link_libraries(monodomain_2d_f PRIVATE opencmisslibs mpi)

install(TARGETS monodomain_2d_f
    DESTINATION bin)


