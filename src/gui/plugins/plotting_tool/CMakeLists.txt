gz_add_gui_plugin(PlottingTool
  SOURCES
    PlottingTool.cc
  QT_HEADERS
    PlottingTool.hh
  PUBLIC_LINK_LIBS
    ${IGNITION-GUI_LIBRARIES}
)
