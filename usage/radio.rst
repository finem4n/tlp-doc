bluetooth, nfc, wifi, wwan
--------------------------
Enable, disable, toggle or check the state of builtin bluetooth, NFC, Wi-Fi and WWAN
(3G/UMTS, 4G/LTE or 5G) radios: ::

        bluetooth [ on | off | toggle ]
        nfc [ on | off | toggle ]
        wifi [ on | off | toggle ]
        wwan [ on | off | toggle ]

Show version: ::

    bluetooth --version
    nfc --version
    wifi --version
    wwan --version

Using the command without arguments displays the actual state.

Hint: for Intel 2200bg and 2915abg cards call the command with :command:`sudo`
or in a root shell.

Prerequisite: the radio device must be supported by the kernel's rfkill framework
(except Intel 2100/2200/2915). This may be checked with :command:`rfkill list`.
