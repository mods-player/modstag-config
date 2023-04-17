**upgradeConfig:**
===
**Add code type selection, Examples:** 
- **run(cpp)**
- **run(c++)**
- **run(c)**
- **run(cs)**
- **run(java)**
- **run(modstag) // The code you intend to do in the future**
- **run(python) // to be continued**
---
**The header files are combined into one, Examples:**
- **@modstag-version 2.0.7 → @modstag-config(version: 2.0.7)**
- **@modstag-version 2.0.7-\n@modstag-version 2.0.6+ → @modstag-config(version: 2.0.6+, version: 2.0.7-)**
- **@modstag-config(cpp) → @modstag-config(mainfile: cpp)
---
Each "cfg.file" needs to reset the code type using "run()".
---
**upgrade2base**
===
null
---
**upgrade16base**
===
null
---
**upgradeColor**
===
Added Italic type colors
---
**The author spits:**
===
The increase from "154KB" to "1369KB" is because I don't have any way to make the corresponding "run" type use the corresponding include without stringing, so I can only distinguish each type separately.
---
I tried to reduce the file size to less than "300KB" if I merged all the duplicates, but the cable problem could not be solved.
---
Tip: I canceled "modstag-program" for this reason too
---
The next version plans to update the header again, expecting to change the colors or make more content
---