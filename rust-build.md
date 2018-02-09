### Make sure you have installed the dependencies:

```sh
g++ 4.7 or later or clang++ 3.x or later
python 2.7 (but not 3.x)
GNU make 3.81 or later
cmake 3.4.3 or later
curl
git
```

### Clone the source with git: (Must Clone Not Download Zip)
```sh
sudo mkdir /opt/rust
cd /opt/rust
git clone https://github.com/rust-lang/rust.git
cd rust
```

### Build
```
./x.py build
```

### Install
```sh
sudo vim /home/google/.bashrc
export PATH="$PATH:/opt/rust/build/x86_64-unknown-linux-gnu/stage1/bin"
```
### Version Check
```sh
./rustc  --version
```
