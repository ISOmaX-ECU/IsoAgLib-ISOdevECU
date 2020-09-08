# Edit following two lines to set component requirements (see docs)
set(COMPONENT_REQUIRES )
set(COMPONENT_PRIV_REQUIRES )

set(COMPONENT_SRCS 
  IsoAgLib-tutorial-private/src/ecu_proprietary_can/component_proprietary_can.cpp
  IsoAgLib-tutorial-private/src/ecu_proprietary_can/component_sensors.cpp
  IsoAgLib-tutorial-private/src/ecu_proprietary_can/ecu_proprietary_can.cpp
  IsoAgLib-tutorial-private/src/common/ecu_common.cpp
  IsoAgLib-tutorial-private/src/common/getoptpp/getopt_pp.cpp
  IsoAgLib-tutorial-private/src/common/tutorial_datastorage.cpp
  IsoAgLib-tutorial-private/src/common/tutorial_eeprom.cpp
  IsoAgLib-tutorial-private/src/platform/esp32/ecu_main_esp32.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/comm/impl/isobus_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/comm/iproprietarybus_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/comm/Part12_DiagnosticsServices/impl/diagnosticfunctionalities_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/comm/Part12_DiagnosticsServices/impl/diagnosticpgnhandler_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/comm/Part12_DiagnosticsServices/impl/diagnosticsservices_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/comm/Part12_DiagnosticsServices/impl/dtccontainer_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/comm/Part3_DataLink/impl/canpkgext_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/comm/Part3_DataLink/impl/chunk_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/comm/Part3_DataLink/impl/multireceive_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/comm/Part3_DataLink/impl/multisendpkg_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/comm/Part3_DataLink/impl/multisend_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/comm/Part3_DataLink/impl/sendstream_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/comm/Part3_DataLink/impl/streamchunk_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/comm/Part3_DataLink/impl/stream_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/comm/Part5_NetworkManagement/impl/baseitem_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/comm/Part5_NetworkManagement/impl/identitem_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/comm/Part5_NetworkManagement/impl/isofilterbox_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/comm/Part5_NetworkManagement/impl/isofiltermanager_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/comm/Part5_NetworkManagement/impl/isoitem_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/comm/Part5_NetworkManagement/impl/isomonitor_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/comm/Part5_NetworkManagement/impl/isoname_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/comm/Part5_NetworkManagement/impl/isorequestpgn_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/comm/Part5_NetworkManagement/impl/istate_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/driver/can/impl/canio_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/driver/can/impl/canpkg_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/driver/can/impl/filterbox_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/driver/can/impl/ident_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/driver/system/impl/system_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/hal/generic_utils/can/canfifo_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/hal/generic_utils/can/canutils.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/hal/generic_utils/system/ThreadWrapper_pthread.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/scheduler/impl/schedulertask_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/scheduler/impl/scheduler_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/util/iassert.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/util/iliberr_c.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/util/impl/flexiblebytestrings.cpp
  IsoAgLib/library/xgpl_src/IsoAgLib/util/impl/util_funcs.cpp
  IsoAgLib/library/xgpl_src/supplementary_driver/driver/datastreams/volatilememorywithsize_c.cpp
  IsoAgLib-tutorial-private/src/IsoAgLib/hal/esp32/can/can_driver_sys.cpp
  IsoAgLib-tutorial-private/src/IsoAgLib/hal/esp32/system/isoaglibthread_c.cpp
  IsoAgLib-tutorial-private/src/IsoAgLib/hal/esp32/system/system_target_extensions.cpp
  IsoAgLib/library/xgpl_src/supplementary_driver/driver/eeprom/impl/eepromio_c.cpp)
  
set(COMPONENT_ADD_INCLUDEDIRS 
  .
  IsoAgLib/library/xgpl_src
  IsoAgLib-tutorial-private/src/ecu_proprietary_can
  IsoAgLib-tutorial-private/src/common
  IsoAgLib-tutorial-private/src/platform/esp32
  IsoAgLib-tutorial-private/src/supplementary_driver/hal/esp32/eeprom)
  
register_component()
