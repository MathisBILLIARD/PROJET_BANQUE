# CMakeList.txt : projet CMake pour PUSH_GIT, incluez la source et définissez
# la logique spécifique au projet ici.
#

# Ajoutez une source à l'exécutable de ce projet.
add_executable (PUSH_GIT "PUSH_GIT.cpp" "PUSH_GIT.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET PUSH_GIT PROPERTY CXX_STANDARD 20)
endif()

# TODO: Ajoutez des tests et installez des cibles si nécessaire.
