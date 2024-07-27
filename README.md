
Linux requirement: https://tauri.app/v1/guides/getting-started/prerequisites

Did not manage to run on Ubuntu:

```
MESA-LOADER: failed to open iris: /opt/amdgpu/lib/x86_64-linux-gnu/dri/iris_dri.so: cannot open shared object file: No such file or directory (search paths /opt/amdgpu/lib/x86_64-linux-gnu/dri, suffix _dri)
failed to load driver: iris
MESA-LOADER: failed to open zink: /opt/amdgpu/lib/x86_64-linux-gnu/dri/zink_dri.so: cannot open shared object file: No such file or directory (search paths /opt/amdgpu/lib/x86_64-linux-gnu/dri, suffix _dri)
failed to load driver: zink
Non-AMD device received in AMD driver.
EGLDisplay Initialization failed: EGL_SUCCESS
Cannot create EGL context: invalid display (last error: EGL_SUCCESS)
```
