add_subdirectory(Valkyrie_Controller)
add_subdirectory(DracoBip_Controller)
add_subdirectory(Atlas_Controller)
add_subdirectory(Mercury_Controller)
add_subdirectory(NAO_Controller)

install(FILES interface.hpp Test.hpp Controller.hpp DESTINATION
    "${INSTALL_INCLUDE_DIR}")
