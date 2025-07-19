# Open Source License Template & Guide

This document serves as a template and guide for choosing the right open-source license for your project. Replace this content with your chosen license text after making your selection.

## Popular Open Source Licenses Overview

### Permissive Licenses

#### MIT License
- **Summary**: Very permissive license with minimal restrictions
- **Key Features**: Allows commercial use, modification, distribution, and private use
- **Requirements**: Must include copyright notice and license text
- **Notable Users**: React, Angular, Node.js, Bootstrap

#### Apache License 2.0
- **Summary**: Permissive license with patent protection
- **Key Features**: Similar to MIT but includes explicit patent grant and trademark protection
- **Requirements**: Must include copyright notice, license text, and state changes
- **Notable Users**: Apache projects, Android, Kubernetes, TensorFlow

#### BSD 3-Clause License
- **Summary**: Permissive license similar to MIT with additional clause
- **Key Features**: Allows commercial use, modification, distribution
- **Requirements**: Must include copyright notice and cannot use project name for endorsement
- **Notable Users**: FreeBSD, Django, Flask

### Copyleft Licenses

#### GNU General Public License v3.0 (GPL-3.0)
- **Summary**: Strong copyleft license ensuring derivative works remain open source
- **Key Features**: Requires derivative works to be licensed under GPL-3.0
- **Requirements**: Must disclose source code, include license text, and state changes
- **Notable Users**: Linux kernel, GIMP, WordPress

#### GNU Lesser General Public License v3.0 (LGPL-3.0)
- **Summary**: Weaker copyleft allowing linking with proprietary software
- **Key Features**: Libraries can be used in proprietary software without making it GPL
- **Requirements**: Must disclose source for LGPL components only
- **Notable Users**: GTK, Qt (dual-licensed), GNU C Library

#### Mozilla Public License 2.0 (MPL-2.0)
- **Summary**: Weak copyleft with file-level scope
- **Key Features**: Only files containing MPL code must remain open source
- **Requirements**: Must disclose source for modified MPL files
- **Notable Users**: Firefox, Thunderbird, LibreOffice

### Creative Commons

#### Creative Commons Zero v1.0 Universal (CC0-1.0)
- **Summary**: Public domain dedication
- **Key Features**: No rights reserved, complete freedom
- **Requirements**: None
- **Notable Users**: SQLite, some government datasets

## License Comparison Table

| License | Type | Commercial Use | Modification | Distribution | Patent Grant | Trademark Use | Disclose Source | License & Copyright Notice | State Changes |
|---------|------|----------------|--------------|--------------|--------------|---------------|-----------------|---------------------------|---------------|
| **MIT** | Permissive | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ✅ | ❌ |
| **Apache 2.0** | Permissive | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | ✅ | ✅ |
| **BSD 3-Clause** | Permissive | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ✅ | ❌ |
| **GPL-3.0** | Strong Copyleft | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ | ✅ | ✅ |
| **LGPL-3.0** | Weak Copyleft | ✅ | ✅ | ✅ | ✅ | ❌ | ✅* | ✅ | ✅ |
| **MPL-2.0** | Weak Copyleft | ✅ | ✅ | ✅ | ✅ | ❌ | ✅** | ✅ | ✅ |
| **CC0-1.0** | Public Domain | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |

**Legend:**
- ✅ = Allowed/Required
- ❌ = Not allowed/Not required
- \* = Only for LGPL components
- \** = Only for modified MPL files

## Choosing the Right License

### Consider These Questions:

1. **Do you want to allow commercial use?**
   - If yes: Most licenses allow this
   - If no: Consider non-commercial Creative Commons licenses (not listed above)

2. **Do you want derivative works to remain open source?**
   - If yes: Choose copyleft (GPL, LGPL, MPL)
   - If no: Choose permissive (MIT, Apache, BSD)

3. **Do you need patent protection?**
   - If yes: Apache 2.0, GPL-3.0, LGPL-3.0, MPL-2.0
   - If no: MIT, BSD are simpler options

4. **Are you creating a library?**
   - For maximum adoption: MIT or Apache 2.0
   - To ensure improvements stay open: LGPL-3.0 or MPL-2.0

5. **Do you want the simplest possible license?**
   - MIT is the most straightforward
   - CC0 if you want to dedicate to public domain

### Quick Recommendations:

- **For most projects**: MIT License (simple, widely understood)
- **For projects needing patent protection**: Apache License 2.0
- **For ensuring derivative works stay open**: GPL-3.0
- **For libraries that should stay open but allow proprietary use**: LGPL-3.0 or MPL-2.0
- **For maximum freedom**: CC0-1.0

## How to Apply Your Chosen License

1. **Replace this entire file** with the full text of your chosen license
2. **Update copyright information** with your name and the current year
3. **Add license headers** to source code files (recommended for some licenses)
4. **Update your README.md** to mention the license
5. **Consider adding a LICENSE badge** to your README

## License Templates

### MIT License Template
```
MIT License

Copyright (c) [year] [fullname]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### Apache License 2.0 Template
```
Apache License
Version 2.0, January 2004
http://www.apache.org/licenses/

[Full Apache 2.0 license text - visit http://www.apache.org/licenses/LICENSE-2.0.txt]
```

## Additional Resources

- [Choose a License](https://choosealicense.com/) - GitHub's license selection tool
- [Open Source Initiative](https://opensource.org/licenses) - Official OSI approved licenses
- [SPDX License List](https://spdx.org/licenses/) - Standardized license identifiers
- [TL;DR Legal](https://tldrlegal.com/) - Plain English license explanations

---

**Note**: This is a template and guide. Replace this content with your actual license text after making your selection. Consider consulting with a lawyer for complex licensing situations.
