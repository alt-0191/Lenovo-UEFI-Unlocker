# Lenovo-UEFI-Unlocker

A backup of [SmokelessRuntimeEFIPatcher](https://github.com/SmokelessCPUv2/SmokelessRuntimeEFIPatcher), sadly it’s 404 until now.

But I found a backup in my drive so I uploaded it.

## How to use it

- Download the zip file from the Release Page
- Extract files in a bootable USB drive
- Turn off safe boot in UEFI settings
- Boot it.

## for Legion Intel 2022 user you need to replace the `SREP_Config.cfg` with this:

```
Op Loaded
H2OFormBrowserDxe
Op Patch
Pattern
49D592C3EB27464F8A119F5DF55A9C8B00000000
49D592C3EB27464F8A119F5DF55A9C8B01000000
Op Patch
Pattern
1AB0E0C17E60754BB8BB0631ECFAACF200000000
1AB0E0C17E60754BB8BB0631ECFAACF201000000
Op Patch
Pattern
9E76D4C6487F2A4D98E987ADCCF35CCC00000000
9E76D4C6487F2A4D98E987ADCCF35CCC01000000
Op Patch
Pattern
732871A65F92C64690B4A40F86A0917B00000000
732871A65F92C64690B4A40F86A0917B01000000
Op End

Op LoadFromFV
SetupUtilityApp
Op Exec
```
