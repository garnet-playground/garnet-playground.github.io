{% include templates/device_specific/firmware_update_oplus_fastbootd.md content="
fastboot flash --slot=all abl abl.img
fastboot flash --slot=all bluetooth bluetooth.img
fastboot flash --slot=all core_nhlos core_nhlos.img
fastboot flash --slot=all devcfg devcfg.img
fastboot flash --slot=all dsp dsp.img
fastboot flash --slot=all engineering_cdt engineering_cdt.img
fastboot flash --slot=all featenabler featenabler.img
fastboot flash --slot=all hyp hyp.img
fastboot flash --slot=all imagefv imagefv.img
fastboot flash --slot=all keymaster keymaster.img
fastboot flash --slot=all modem modem.img
fastboot flash --slot=all oplus_sec oplus_sec.img
fastboot flash --slot=all oplusstanvbk oplusstanvbk.img
fastboot flash --slot=all qupfw qupfw.img
fastboot flash --slot=all rpm rpm.img
fastboot flash --slot=all splash splash.img
fastboot flash --slot=all tz tz.img
fastboot flash --slot=all uefisecapp uefisecapp.img
fastboot flash --slot=all xbl_config xbl_config.img
fastboot flash --slot=all xbl xbl.img
" %}
