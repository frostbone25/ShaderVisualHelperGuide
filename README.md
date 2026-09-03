# ShaderVisualHelperGuide

A simple documentation repository containing a collection of notes and screenshots to assist with shader development when checking vectors and how they should look when displayed visually. Often times we can forget what certain vectors are supposed to look like visually when checking terms.

#### Table of Contents

- [Screen UVs](#screen-uvs)

# Screen UVs

#### DirectX

![screen-uv-normalized-directx.png](content/screen-uv-normalized-directx.png)

This is showing a normalized UV screen coordinate. Normalized meaning it's values between ***(0...1)***. It is comprised of two vectors, x and y. 

In DirectX convention...
- X / R / Horizontal Axis: From Left to Right is 0 to 1
- Y / G / Vertical Axis: From Up to Down is 0 to 1

#### OpenGL

![screen-uv-normalized-directx.png](content/screen-uv-normalized-opengl.png)

This is showing a normalized UV screen coordinate. Normalized meaning it's values between ***(0...1)***. It is comprised of two vectors, x and y. 

In OpenGL convention...
- X / R / Horizontal Axis: From Left to Right is 0 to 1
- Y / G / Vertical Axis: From Up to Down is 1 to 0

# End

More to come in the future for different common shader terms, any corrections or additions just make a pull request.