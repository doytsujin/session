liri_add_module(Session
    DESCRIPTION
        "Session manager"
    SOURCES
        sessionmodule.cpp
        sessionmodule.h
        sessionmodule_p.h
    FORWARDING_HEADERS
        SessionModule
    PRIVATE_HEADERS
        sessionmodule_p.h
    DEFINES
        QT_NO_CAST_FROM_ASCII
        QT_NO_FOREACH
    PUBLIC_LIBRARIES
        Qt5::Core
    PKGCONFIG_DEPENDENCIES
        Qt5Core
)
