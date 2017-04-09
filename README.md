# android_device_huawei_rio

Crear .repo/local_manifests/local_manifest.xml, y pega este contenido : 

<?xml version="1.0" encoding="UTF-8"?>
<manifest>
  <project name="allurba/android_device_huawei_rio" path="device/huawei/rio" remote="github" revision="slim7.1" />
  <project name="Huawei-Dev/android_kernel_huawei_msm8939" path="kernel/huawei/msm8939" remote="github" revision="7.1.1" />
  <project name="Huawei-Dev/android_vendor_huawei_rio" path="vendor/huawei/rio" remote="github" revision="7.1.1" />
  <project name="LineageOS/android_packages_resources_devicesettings" path="packages/resources/devicesettings" remote="github"
revision="cm-14.1" />
</manifest>
