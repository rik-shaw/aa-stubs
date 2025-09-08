# Android Auto "Stub Apps" for Google Components

This is a simple consolidation of the "stub apps" needed to avoid installing the corresponding Google components needed to use *Android Auto* on de-Googled Android ROMs.

For [iodéOS](https://iode.tech) or other ROMs which include a spoofed Android Auto stub at the root level, you do *not need to root* your device with Magisk or other to setup and use Android Auto, but can follow these basic steps:
1. Activate *Android Auto* from *"System Settings > Apps > Pre-Installed Apps"*
2. Update *Android Auto* from the Aurora Store *(to install the actual Android Auto package)*
3. Install these stub apps
4. Grant the relevant permissions
5. Use *Android Auto*!

[This guide](https://iode.tech/documentation/android-auto/) from the iodé documentation gives more information on this process.

For ROMs that *do not have Android Auto integration at the root level* such as [LineageOS for microG](https://lineage.microg.org) you will need to root using Magisk or other, following guidance from the [aa4mg project](https://github.com/sn-00-x/aa4mg/).

Credit for the `Maps.apk` stub app goes to [aa4mg](https://github.com/sn-00-x/aa4mg/). Credit for the `gappsstub.apk` and `speech-services-stub.apk` stub apps goes to [SolidEva](https://github.com/SolidEva/android-auto-stub/).