### TCP

This TCP service creates a TCP/IP socket, binds the socket to a port and listens
for incoming connections.

### Build and run service

```
  mkdir build
  cd build
  conan install .. -pr <profile-name>
  source activate.sh
  cmake ..
  cmake --build .
  boot tcp_example
  source deactivate.sh
```
