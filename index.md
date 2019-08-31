
`smbcmp` is a small tool designed to diff and compare network
captures, specifically aimed at SMB traffic. It leverages
[wireshark](https://wireshark.org) to dissect and do deep analysis of
SMB packets and supports SMB1, SMB2 and SMB3.

<asciinema-player src="/demo.cast" cols="78" rows="26"></asciinema-player>

# Features

  * Compare captures side-by-side
  * Ignore specific fields
  * Leverages [Wireshark](https://wireshark.org) for deep analyzing and dissecting:
      * Compares decrypted SMB3 traffic (AES-128-GCM & AES-128-CCM, given keys are available)
      * Compares decompressed traffic (LZ77, LZNT1, LZ77+Huff)
      * Supports SMB1, SMB2, SMB3
      * Supports all sorts of capture format
  
  * Available on Linux and Windows (soon)
  * [Free and open source](https://github.com/smbcmp/smbcmp) (GPLv3)
  * console version based on ncurses
  * GUI version based on wxWidget

# Download

* [Github](https://github.com/smbcmp/smbcmp)


