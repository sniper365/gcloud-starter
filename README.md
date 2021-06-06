# gcloud-cpp-starter

Starter project. A web server and client fully made with C++/WebAssembly. A
simple CMake configuration describes how to build and run everything.

Features:
 * Client uses a [C++ virtual dom](https://github.com/mbasso/asm-dom).
 * Server runs on [Google cloud functions](https://cloud.google.com/functions/docs/concepts/overview).

Demo: [here](https://arthursonzogni.github.io/gcloud-cpp-starter/)

# How to build?

* Build everything using CMake:
~~~bash
mkdir build
cd build
emcmake cmake ..
make
make run
~~~

* Deploy the server locally using the emulator:
~~~bash
make deploy
~~~

* Serve the client locally and open it using a web browser:
~~~bash
make run
~~~
