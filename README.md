# fastboot3ds-Sighaxed
Personal fastboot3DS mod with Sighax signature

<img src="https://github.com/daviiid99/fastboot3ds-Sighaxed/blob/main/logo.png">
This fastboot3ds mod includes the sighax signature, in other words, the signature needed to copy the fastboot3ds payload directly into your FIRM0 or/and FIRM1 partition,making the installation easy with GodMode9 scripts.
<br/>
<br/>

<b>Sighax signature (in hex):</b><br/>
```
unsigned char ucDataBlock[256] = {
	<br/>// Offset 0x00000000 to 0x00000255
	0xB6, 0x72, 0x45, 0x31, 0xC4, 0x48, 0x65, 0x7A, 0x2A, 0x2E, 0xE3, 0x06,<br/>
	0x45, 0x7E, 0x35, 0x0A, 0x10, 0xD5, 0x44, 0xB4, 0x28, 0x59, 0xB0, 0xE5,<br/>
	0xB0, 0xBE, 0xD2, 0x75, 0x34, 0xCC, 0xCC, 0x2A, 0x4D, 0x47, 0xED, 0xEA,<br/>
	0x60, 0xA7, 0xDD, 0x99, 0x93, 0x99, 0x50, 0xA6, 0x35, 0x7B, 0x1E, 0x35,<br/>
	0xDF, 0xC7, 0xFA, 0xC7, 0x73, 0xB7, 0xE1, 0x2E, 0x7C, 0x14, 0x81, 0x23,<br/>
	0x4A, 0xF1, 0x41, 0xB3, 0x1C, 0xF0, 0x8E, 0x9F, 0x62, 0x29, 0x3A, 0xA6,
	<br/>0xBA, 0xAE, 0x24, 0x6C, 0x15, 0x09, 0x5F, 0x8B, 0x78, 0x40, 0x2A, 0x68,<br/>
	0x4D, 0x85, 0x2C, 0x68, 0x05, 0x49, 0xFA, 0x5B, 0x3F, 0x14, 0xD9, 0xE8,<br/>
	0x38, 0xA2, 0xFB, 0x9C, 0x09, 0xA1, 0x5A, 0xBB, 0x40, 0xDC, 0xA2, 0x5E,<br/>
	0x40, 0xA3, 0xDD, 0xC1, 0xF5, 0x8E, 0x79, 0xCE, 0xC9, 0x01, 0x97, 0x43,<br/>
	0x63, 0xA9, 0x46, 0xE9, 0x9B, 0x43, 0x46, 0xE8, 0xA3, 0x72, 0xB6, 0xCD,<br/>
	0x55, 0xA7, 0x07, 0xE1, 0xEA, 0xB9, 0xBE, 0xC0, 0x20, 0x0B, 0x5B, 0xA0,<br/>
	0xB6, 0x61, 0x23, 0x6A, 0x87, 0x08, 0xD7, 0x04, 0x51, 0x7F, 0x43, 0xC6,<br/>
	0xC3, 0x8E, 0xE9, 0x56, 0x01, 0x11, 0xE1, 0x40, 0x5E, 0x5E, 0x8E, 0xD3,<br/>
	0x56, 0xC4, 0x9C, 0x4F, 0xF6, 0x82, 0x3D, 0x12, 0x19, 0xAF, 0xAE, 0xEB,<br/>
	0x3D, 0xF3, 0xC3, 0x6B, 0x62, 0xBB, 0xA8, 0x8F, 0xC1, 0x5B, 0xA8, 0x64,<br/>
	0x8F, 0x93, 0x33, 0xFD, 0x9F, 0xC0, 0x92, 0xB8, 0x14, 0x6C, 0x3D, 0x90,<br/>
	0x8F, 0x73, 0x15, 0x5D, 0x48, 0xBE, 0x89, 0xD7, 0x26, 0x12, 0xE1, 0x8E,<br/>
	0x4A, 0xA8, 0xEB, 0x9B, 0x7F, 0xD2, 0xA5, 0xF7, 0x32, 0x8C, 0x4E, 0xCB,<br/>
	0xFB, 0x00, 0x83, 0x83, 0x3C, 0xBD, 0x5C, 0x98, 0x3A, 0x25, 0xCE, 0xB8,<br/>
	0xB9, 0x41, 0xCC, 0x68, 0xEB, 0x01, 0x7C, 0xE8, 0x7F, 0x5D, 0x79, 0x3A,<br/>
	0xCA, 0x09, 0xAC, 0xF7<br/>
}
```
<br/>

<b>Grab the latest mod from:<b/> <a href="https://github.com/daviiid99/fastboot3ds-Sighaxed/releases">Releases</a>
