# android_device_huawei_rio

You need to create .repo/local_manifests/android_manifest.xml, and put this content : 

<?xml version="1.0" encoding="UTF-8"?>
<manifest>
  <project name="allurba/android_device_huawei_rio" path="device/huawei/rio" remote="github" revision="aicp" />
  <project name="Huawei-Dev/android_kernel_huawei_msm8939" path="kernel/huawei/msm8939" remote="github" revision="7.1.1" />
  <project name="Huawei-Dev/android_vendor_huawei_rio" path="vendor/huawei/rio" remote="github" revision="7.1.1" />
  <project name="allurba/vendor_aicp_products" path="vendor/aicp/products" remote="github" revision="master" />
  <project name="LineageOS/android_device_qcom_common" path="device/qcom/common" remote="github" />
  <project name="LineageOS/android_packages_resources_devicesettings" path="packages/resources/devicesettings" remote="github" revision="cm-14.1"/>
  <project name="LineageOS/android_packages_apps_FlipFlap" path="packages/apps/FlipFlap" remote="github" revision="cm-14.1"/>
  <project name="LineageOS/android_external_sony_boringssl-compat" path="external/sony/boringssl-compat" remote="github" revision="cm-14.1"/>
  <project name="LineageOS/android_external_stlport" path="external/stlport" remote="github" revision="cm-14.1"/>
</manifest>


