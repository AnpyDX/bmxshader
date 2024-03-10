# BMX Shader
**bmxshader** is a convenient and useful shader file format, which helps orginze *GLSL* code easily.

This repo contains **bmxshader** c++ interface and the source code of **bmxshader** validator and compiler.

## overview
**Repo Structure**

- **bmxshader** -> *bmxshader c++ interface*
- **bmxshaderc-src** -> *bmxshader compiler source code*
- **thirdparty** -> *neccessary third party libraries*

## requirements
- C++ 14 compiler.
- CMake 3.8+
- [glslc](https://github.com/KhronosGroup/glslang) (executable release).

**NOTE: To make bmxshaderc works, you need to download glslc binrary first.**

**NOTE:**
**To compile & validate GLSL code, bmxshader-compiler needs glslc binrary to do this job. However, as compiling glslc source with bmxshader may introduce some tricky problems, we decided use glslc as an external executable. So you need to download glslc binrary release and put them in the same directory.**

## documentation
More details can be found in [documentation](docs/index.md).

## license
Licensed under the MIT license, read [LICENSE](LICENSE) for details.