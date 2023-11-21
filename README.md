# CS133

## Source

```sh
source /tools/Xilinx/Vitis_HLS/2023.1/settings64.sh 
source /opt/xilinx/xrt/setup.sh
source /opt/merlin/sources/merlin-compiler/merlin_setting.sh
export C_INCLUDE_PATH="/tools/Xilinx/Vitis_HLS/2023.1/include:$C_INCLUDE_PATH"
export CPLUS_INCLUDE_PATH="/tools/Xilinx/Vitis_HLS/2023.1/include:$CPLUS_INCLUDE_PATH"
```

## Run

```sh
git clone git@github.com:S12P/cs133.git
cd cs133
make mcc_estimate
```


