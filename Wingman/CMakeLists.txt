#
# This file was genared by ./proj2cmake and will be overwritten on it's next run!
# Please put all configurations in the cmake_conf/*.cmake files.
#

cmake_minimum_required(VERSION 2.8)


INCLUDE("Wingman.cmake")

ADD_EXECUTABLE(Wingman
            ${Wingman_SRC})

TARGET_LINK_LIBRARIES(Wingman
            ${Wingman_DEPS}
            ${Wingman_ADDITIONAL_DEPS}
            ${SOLUTION_APP_DEPS}
            ${SOLUTION_GENERAL_DEPS}
            ${CONAN_TARGETS})

