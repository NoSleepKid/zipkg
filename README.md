# zipkg

> [!WARNING]
> **Arch Linux only (officially).**
>
> **Windows users:** use `winget` or download software from the official website  
> **macOS users:** use `brew`, `.dmg` installers, or the official website  

> [!NOTE]
> **Other Linux distributions:**  
> zipkg may work with modifications, but it is **not officially supported** outside of Arch and Arch-based distributions.  
> Expect manual tweaks, breakage, and zero guarantees.

zipkg is a lightweight, Python-based package manager built specifically for Arch Linux and Arch-based distributions.  
It is designed to be fast, minimal, and script-friendly while staying true to Arch principles.

When running on Arch Linux, zipkg integrates directly with the Arch User Repository (AUR), allowing access to both official repository packages and community-maintained AUR packages through a single, consistent interface.

Rather than replacing existing tools, zipkg acts as a thin layer on top of the Arch package ecosystem, focusing on clarity, speed, and automation without unnecessary abstraction.

## Usage

```bash
zipkg [option] <package>
```
![Test Image 8](https://raw.githubusercontent.com/tograh/testrepository/master/3DTest.png)
