# openwrt-ax1800-ipq6k-20241228-buildok
ipq600 ax1800 编译正常

源码来源：https://github.com/FKDXD/openwrt-gl-ax1800，应该都来源于gl-ax1800

原主源码错误很多，除了rust以外都修订好了:希望有高手能解决
由于能力有限本源码不能./scripts/feeds install -a -f


Distributor ID: Ubuntu

Description:    Ubuntu 18.04.6 LTS

Release:        18.04

Codename:       bionic

GOVERSION='go1.22.10'

gcc --version
gcc (Ubuntu 11.4.0-2ubuntu1~18.04) 11.4.0
Copyright (C) 2021 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

g++ (Ubuntu 11.4.0-2ubuntu1~18.04) 11.4.0
Copyright (C) 2021 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

Generating index for package ./xz-utils_5.2.5-2_aarch64_cortex-a53.ipk

Generating index for package ./zerotier_1.10.6-1_aarch64_cortex-a53.ipk

Generating index for package ./zipcmp_1.8.0-4_aarch64_cortex-a53.ipk

Generating index for package ./zipmerge_1.8.0-4_aarch64_cortex-a53.ipk

Generating index for package ./ziptool_1.8.0-4_aarch64_cortex-a53.ipk

Generating index for package ./zlib_1.2.11-3_aarch64_cortex-a53.ipk

Generating index for package ./zstd_1.3.8-1_aarch64_cortex-a53.ipk

Signing package index...

make[2]: Leaving directory '/openwrt/openwrt-gl-ax1800-f937182905-202412-tools.ok'

export MAKEFLAGS= ;make -w -r json_overview_image_info

make[2]: Entering directory '/openwrt/openwrt-gl-ax1800-f937182905-202412-tools.ok'

make[2]: Nothing to be done for 'json_overview_image_info'.

make[2]: Leaving directory '/openwrt/openwrt-gl-ax1800-f937182905-202412-tools.ok'

export MAKEFLAGS= ;make -w -r checksum

make[2]: Entering directory '/openwrt/openwrt-gl-ax1800-f937182905-202412-tools.ok'

make[2]: Leaving directory '/openwrt/openwrt-gl-ax1800-f937182905-202412-tools.ok' 

make[1]: Leaving directory '/openwrt/openwrt-gl-ax1800-f937182905-202412-tools.ok'

@ub18ip18:/openwrt/openwrt-gl-ax1800-f937182905-202412-tools.ok$ find bin|grep ssr-plus

bin/targets/ipq60xx/generic/packages/luci-app-ssr-plus_188-3_all.ipk

bin/targets/ipq60xx/generic/packages/luci-i18n-ssr-plus-zh-cn_188-3_all.ipk

@ub18ip18:/openwrt/openwrt-gl-ax1800-f937182905-202412-tools.ok$ find bin|grep passwall

bin/targets/ipq60xx/generic/packages/luci-app-passwall_24.12.17-2_all.ipk

bin/targets/ipq60xx/generic/packages/luci-i18n-passwall-zh-cn_24.12.17-2_all.ipk

@ub18ip18:/openwrt/openwrt-gl-ax1800-f937182905-202412-tools.ok$ find bin|grep openclash

bin/targets/ipq60xx/generic/packages/luci-app-openclash_0.46.050-beta_all.ipk
