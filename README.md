# Android Auto Google App Stubs

This is a simple consolidation of the "stub apps" needed to avoid installing the corresponding Google apps for Android Auto on de-Googled Android ROMs. For [iodéOS](https://iode.tech), which includes a spoofed Android Auto stub at the root level, you do *not need to root* your device with Magisk or other to setup and use Android Auto, but can simply activate Android Auto, update it *(to install the actual Android Auto package)*, install these stubs in place of the Google components, grant the relevant permissions, and then you are set to go! [This guide](https://iode.tech/documentation/android-auto/) from the iodé documentation gives more information on this process.

For ROMs that *do not have Android Auto integration at the root level,* you will need to use Magisk or other, following guidance from the [aa4mg project](https://github.com/sn-00-x/aa4mg/).

Credit for the `Maps.apk` stub app goes to [aa4mg](https://github.com/sn-00-x/aa4mg/). Credit for the `gappsstub.apk` and `speech-services-stub.apk` stub apps goes to [SolidEva](https://github.com/SolidEva/android-auto-stub/).