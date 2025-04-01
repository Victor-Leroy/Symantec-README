# 🛡️ Symantec Software Package – Third-Party Notices

**© 2006 Symantec Corporation. All rights reserved.**  
Symantec and the Symantec logo are trademarks or registered trademarks of Symantec Corporation or its affiliates in the U.S. and other countries.  
Other names may be trademarks of their respective owners.

---

## 📂 General Information

**Title**: Third-Party Licenses and Notices for Symantec Product  
**Maintained by**: Symantec Legal and Product Development Teams  
**Contact**: [Symantec Support](https://www.broadcom.com/support/security-center)  
**License Type**: Mixed – proprietary core with bundled third-party open-source components  
**Last Updated**: 2006

---

## 📄 File Overview

| Filename                            | Description                                                                 |
|------------------------------------|-----------------------------------------------------------------------------|
| `README.md`                        | This file. Overview and third-party licensing info                          |
| `ThirdPartyLegalNoticeAppendix.pdf`| [Boost and TinyXML licensing](https://techdocs.broadcom.com/us/en/symantec-security-software/web-and-network-security/threat-explorer/all/third-party-legal-notices.html) |
| `ThirdPartyLegalReadMe.txt`        | [Additional licensing information](https://www.veritas.com/support/en_US/doc/103228346-147587303-0/v95611504-147587303) |

---

## ⚙️ Configuration & Installation

This Symantec product includes embedded third-party components that may be dynamically or statically linked as part of the build or deployment process. Although end users typically do not need to install or configure these libraries manually, the following information may be relevant for developers, compliance officers, or enterprise IT administrators:

### 🔧 Configuration Details

- **Third-party components are pre-integrated** in the distributed binaries and do not require separate installation.
- These components are used internally to support software features such as:
  - Data parsing and serialization (via TinyXML)
  - Utility functions, type handling, and memory management (via Boost)
- No user-facing configuration files are associated with the third-party libraries.
- There is no requirement to expose or reconfigure these components during typical end-user deployment.

### 🛠️ Installation Notes

- The product is distributed as a complete package and can be installed using the standard Symantec installer.
- No additional installation steps are required for the Boost or TinyXML libraries.
- If compiling the product from source (internal builds only):
  - Ensure Boost v1.33.1 and TinyXML v2.4.0 are included in the source tree or referenced in your build system.
  - Use a compatible compiler (GCC/MSVC) and ensure the license terms are respected during redistribution.
- Source and binary distributions may vary by region or product SKU; consult internal documentation or support for build instructions.

### 📌 Compliance Reminder

> **Developers and integrators**: If you redistribute the product or create derivative works based on this package, ensure the license terms of Boost and TinyXML are followed.  
> Include the license texts and attributions in all binary and source releases as required.



---

## 📜 Third-Party Licenses

### 🔹 Boost v1.33.1

- **Authors**: Beman Dawes, David Abrahams, Rene Rivera
- **License**: [Boost Software License v1.0 (2003)](https://www.boost.org/users/license.html)

> Permission is granted to use, reproduce, display, distribute, and modify the Software. Attribution and license notice required.  
> Distributed **"AS IS"**, without warranties.

---

### 🔸 TinyXML v2.4.0

- **Author**: Lee Thompson  
- **License**: [zlib License](https://github.com/leethomason/tinyxml/blob/master/tinyxml.h)

> Freely usable and modifiable, including for commercial use.  
> Attribution preferred but not required.  
> Altered versions must be marked as such.

---

## ⚠️ Known Limitations

- These third-party notices apply **only** to the versions bundled with this Symantec product.
- For updates or modifications, refer to respective upstream projects.

---

## 🧾 Legal & Licensing

This software package and accompanying documentation are classified as:

> "Commercial Computer Software" and "Commercial Computer Software Documentation" under FAR 12.212 and DFARS 227.7202.

For full legal details, consult [Symantec Terms of Service](https://www.broadcom.com/company/legal) or contact support.

---

## 📬 Contact & Support

- 📞 Symantec Security Support: [https://www.broadcom.com/support](https://www.broadcom.com/support)
- 📚 Product Documentation: [https://techdocs.broadcom.com](https://techdocs.broadcom.com)

---

