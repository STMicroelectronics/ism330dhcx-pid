---
pagetitle: Release Notes for ISM330DHCX Component
lang: en
header-includes: <link rel="icon" type="image/x-icon" href="_htmresc/favicon.png" />
---

::: {.row}
::: {.col-sm-12 .col-lg-4}

<center>
# Release Notes for ISM330DHCX Component Driver
Copyright &copy; 2021 STMicroelectronics\

[![ST logo](_htmresc/st_logo_2020.png)](https://www.st.com){.logo}
</center>

# License

This software component is licensed by ST under BSD 3-Clause license, the "License".
You may not use this component except in compliance with the License. You may obtain a copy of the License at:

[BSD 3-Clause license](https://opensource.org/licenses/BSD-3-Clause)

# Purpose

This directory contains the ISM330DHCX component drivers.
:::

::: {.col-sm-12 .col-lg-8}
# Update history

::: {.collapse}
<input type="checkbox" id="collapse-section1" aria-hidden="true">
<label for="collapse-section1" aria-hidden="true">V1.0.0 / 18-June-2021</label>
<div>

## Main changes

### First release

- First official release [ref. DS v4.0]

##

</div>

<input type="checkbox" id="collapse-section2" aria-hidden="true">
<label for="collapse-section2" aria-hidden="true">V1.1.0 / 01-June-2023</label>
<div>

## Main changes

- ism330dhcx driver: Fixed most mcuastyle errors
- ism330dhcx_reg.h: Fixed compilation warning with MDK-ARM
- ism330dhcx_reg.h: Extend stmdev_ctx_t structure with mdelay callback
- repo name changed adding '-pid' extension.
- ism330dhcx driver: Added __weak directive to I/O routines

##

</div>

<input type="checkbox" id="collapse-section3" aria-hidden="true">
<label for="collapse-section3" aria-hidden="true">V2.0.0 / 18-Jan-2024</label>
<div>

## Main changes

- Add "const" to ctx arg for all APIs

##

</div>

<input type="checkbox" id="collapse-section4" aria-hidden="true">
<label for="collapse-section4" aria-hidden="true">V2.0.1 / 19-Mar-2024</label>
<div>

## Main changes

- Fixed code style (Artistic Style Version 3.4.13)

##

</div>

<input type="checkbox" id="collapse-section5" aria-hidden="true">
<label for="collapse-section5" aria-hidden="true">V2.0.2 / 19-Jun-2024</label>
<div>

## Main changes

- updated README.md file with tag reference and mdelay description

##

</div>

<input type="checkbox" id="collapse-section6" aria-hidden="true">
<label for="collapse-section6" aria-hidden="true">V2.0.3 / 03-Oct-2024</label>
<div>

## Main changes

- Fix from_lsb_to_nsec() API overflow

##

</div>

<input type="checkbox" id="collapse-section7" aria-hidden="true">
<label for="collapse-section7" aria-hidden="true">V2.1.0 / 18-Dec-2024</label>
<div>

## Main changes

- Read always both FIFO_STATUS1 and FIFO_STATUS2 regs
- Fix fifo_watermark_set() API
- align driver among ism330dhcx/lsm6dsrx/lsm6dsr
- Fix from_lsb_to_nsec() API

##

</div>

<input type="checkbox" id="collapse-section8" aria-hidden="true">
<label for="collapse-section8" aria-hidden="true">V2.1.1 / 07-Apr-2025</label>
<div>

## Main changes

- Fix MISRA C Errors

##

</div>

<input type="checkbox" id="collapse-section9" aria-hidden="true">
<label for="collapse-section9" aria-hidden="true">V2.2.0 / 01-Jul-2025</label>
<div>

## Main changes

- Align to lsm6dsr/lsm6dsrx drivers style
- Fix driver formatting options
- Added pointer to private data in stmdev_ctx_t

##

</div>

<input type="checkbox" id="collapse-section10" aria-hidden="true">
<label for="collapse-section10" aria-hidden="true">V2.3.0 / 07-Jul-2025</label>
<div>

## Main changes

- change sh_read_data_raw_get() API
- Fix fsm_number_of_programs_set API
- changed API name into drdy_mask_set/get
- Fix few typos

##

</div>

<input type="checkbox" id="collapse-section11" checked aria-hidden="true">
<label for="collapse-section11" aria-hidden="true">V2.4.0 / 07-Oct-2025</label>
<div>

## Main changes

- Aligned ln_pg_write/read implementations
- Added checks before writes and membank setting
- Adding CODE_OF_CONDUCT.md and SECURITY.md
- Fix all_sources_get API

##

</div>
:::



:::
:::

<footer class="sticky">
::: {.columns}
::: {.column width="95%"}
For complete documentation on ISM330DHCX,
visit:
[ISM330DHCX](https://www.st.com/content/st_com/en/products/mems-and-sensors/inemo-inertial-modules/ism330dhcx.html)
:::
::: {.column width="5%"}
<abbr title="Based on template cx566953 version 2.0">Info</abbr>
:::
:::
</footer>
