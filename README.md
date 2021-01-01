# Introduction-to-3D-Game-Programming-with-DirectX9.0
> This is a source code of DirectX 9.0

</br>

### Environment

- [VS 2019](https://visualstudio.microsoft.com/zh-hant/vs/)
- [DirectX 9.0 SDK](https://www.microsoft.com/en-us/download/details.aspx?id=6812)

</br>

### DirectX 9.0 setup with Visual Studio

- **Step 1**

Download and install the **DXSDK_Jun 10**.

</br>

- **Step 2**

In project, right click on the **project**, and select properties.

</br>

- **Step 3**

To the **VC++ Directory**

**Include Directory** add `C:\Program Files (x86)\Microsoft DirectX SDK (June 2010)\Include` (add your path)

**Library Directory** add `C:\Program Files (x86)\Microsoft DirectX SDK (June 2010)\Lib\x86` (add your path)

</br>

- **Step 4**

To the **Linker**

**Other Dependencies** add

- d3d9.lib
- d3dx9.lib
- winmm.lib
