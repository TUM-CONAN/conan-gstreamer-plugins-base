GStreamer-Plugins-Base

notes:
- building with opengl:
  ```
    export PKG_CONFIG_PATH=/usr/lib/x86_64-linux-gnu/pkgconfig:/usr/lib/pkgconfig:/usr/share/pkgconfig
    export PKG_CONFIG_SYSTEM_PATH=/usr/lib/x86_64-linux-gnu/pkgconfig:/usr/lib/pkgconfig:/usr/share/pkgconfig
    conan create . camposs/stable -o gstreamer-plugins-base:gl=True -o gstreamer-plugins-base:x11=True
  ```