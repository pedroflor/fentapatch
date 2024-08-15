### fentapatch

---

**Fork from: https://github.com/osirislab/Fentanyl**

Original developer: "OSIRIS Lab"

---

**fentapatch** is an IDAPython script that simplifies the patching process. It allows you to easily patch from IDA Pro or Demo without needing to use a hex editor for most tasks, though you can edit raw bytes via IDA's hex view if necessary. It also supports undoing and redoing changes to the idb.

Support more architectures than just x86 and x86_64. It automates common patching tasks and one of its best features is the support for Undo/Redo, allowing you to see changes live on the graph and undo them if needed.

---

**Tested on IDA Pro 9.0.2 Linux**

---

**INSTALL**

1) Download this repo
2) Copy `icons`, `py3`, `fentapatch.py` to `/PATH/to/IDA-PRO-LINUX/plugins/`
3) Enjoy it!

---

**Screenshot**

![image](https://github.com/user-attachments/assets/ee4a196c-7612-4d11-a9d2-d1af59b9e5a1)

---

**Weird relationship in graph**

If you see this line, it's not related to this plugin... the fault is from IDA :)

**Fix**: `IDA Pro -> Windows -> Reset desktop`

![image](https://github.com/user-attachments/assets/ac69d735-c6f9-49fc-a5ca-15aac9c47699)

---

**Bug fixes and bug reports are wellcome!!!**
