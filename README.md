# Grasp_pipeline
<a name="Install the GPD python binding"></a>
## 1) Install the GPD python binding
```
git clone https://github.com/patricknaughton01/gpd  
cd gpd
git clone https://github.com/pybind/pybind11
mkdir build
cd build
cmake .. -DBUILD_PYTHON=ON
make -j
```
<a name="Install AprilTag"></a>
## 1) Install AprilTag
```
git clone https://github.com/Tinker-Twins/AprilTag.git
cd ~/AprilTag
./install.sh
```
