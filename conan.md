$ conan install . --output-folder=build --build=missing  
```
gtest/1.14.0: Running CMake.build()
...
gtest/1.14.0: Running CMake.install()
gtest/1.14.0: RUN: cmake --install "/Users/gsimsek/.conan2/p/b/gtestd00e8d2331da6/b/build/Release"
  --prefix "/Users/gsimsek/.conan2/p/b/gtestd00e8d2331da6/p"
-- Install configuration: "Release"
-- Installing: /Users/gsimsek/.conan2/p/b/gtestd00e8d2331da6/p/include
```

$ conan profile detect --force  
```
detect_api: Found clang 17.0
detect_api: clang>=8, using the major as version

Detected profile:
[settings]
arch=x86_64
build_type=Release
compiler=clang
compiler.cppstd=gnu17
compiler.libcxx=libc++
compiler.version=17
os=Macos

WARN: This profile is a guess of your environment, please check it.
WARN: Defaulted to cppstd='gnu17' for apple-clang.

Saving detected profile to /Users/gsimsek/.conan2/profiles/default
```

$ conan profile path default   
`/Users/user/.conan2/profiles/default` 


