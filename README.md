# Lua
CMake based build of Lua 5.4.0-beta
# Usage
Inside of CMakeLists.txt
```
add_subdirectory(lua)
...
target_link_libraries(<YOURTARGET> lua_static)
```
