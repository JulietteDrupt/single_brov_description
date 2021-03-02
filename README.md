# single_brov_description

Note : in order to control the single bluerov (launch file upload_brov_sdf.launch), copy folder brov_1 from single_brov_description/addtoUUVPackage/cascadedControl/ to uuv_simulator/uuv_control/uuv_control_cascaded_pids/config/ and folder brov_1 from single_brov_description/addtoUUVPackage/thrusterManager/ to uuv_simulator/uuv_control/uuv_thruster_manager/config/

```
cp -a single_brov_description/addtoUUVPackage/cascadedControl/. <your path>/uuv_simulator/uuv_control/uuv_control_cascaded_pids/config/
cp -a single_brov_description/addtoUUVPackage/thrusterManager/. <your path>/uuv_simulator/uuv_control/uuv_thruster_manager/config
```
