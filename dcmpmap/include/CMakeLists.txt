# declare installation files
INSTALL(DIRECTORY dcmtk/dcmpmap DESTINATION "${DCMTK_INSTALL_INCDIR}/dcmtk" COMPONENT include FILES_MATCHING PATTERN "*.h" PATTERN "CVS" EXCLUDE)
