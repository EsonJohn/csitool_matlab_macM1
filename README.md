# csitool_matlab_macM1
Matlab script built on Macbook Air M1, which is used to parse csi raw data collected from Intel 5200 NIC

The original Windows-based scripts are from https://github.com/dhalperi/linux-80211n-csitool-supplementary

Script usage:

For 1x3 MIMO setting:
[csi_data, timestamp] = csi_get_all(CSI_file_path);

For 2x3 MIMO setting:
[csi_data, timestamp] = csi_get_all_23(CSI_file_path);

For 3x3 MIMO setting:
[csi_data, timestamp] = csi_get_all_33(CSI_file_path);
