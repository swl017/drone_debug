# PX4 Gain Setting
QGroundControl > Parameters

## Airframe
- 3DR Iris Quarotor

## Sensor

## Parameters
### Command
| name | default | tuned value | unit |
| ---  | ---     | ---         | ---  |
| `COM_ARM_EKF_AB` | 0.002 | 0.0022 | m/s |
| `COM_ARM_EKF_GB` | 0.001 | 0.0011 | rad |
| `COM_ARM_MAG_ANG` | 45 | 30 | deg |
| `COM_DISARM_LAND` | 2.00 | 10.00 | s |
| `COM_FLTMODE1` | - | - | - |

### EKF2
| name | default | tuned value | unit |
| ---  | ---     | ---         | ---  |
| `EKF2_AID_MASK` | 1 | **280** | - |
| `EKF2_HGT_MODE` | Baro | Vision | - |
| `EKF2_OF_DELAY` | - | - | - |
> `EKF2_AID_MASK` = 280
> - vision position fusion
> - vision yaw fusion
> - vision velocity fusion


### MAVLink 
| name | default | tuned value | unit |
| ---  | ---     | ---         | ---  |
| `MAV_1_CONFIG` | - | **TELEM 2** | - |

### Mission
| name | default | tuned value | unit |
| ---  | ---     | ---         | ---  |
| `NAV_RCL_ACT` | Return mode | **Return mode** | - |

### Multicopter Attitude Control
| name | default | tuned value | unit |
| ---  | ---     | ---         | ---  |
| `MC_PITCHRATE_MAX` | 220.0 | **220.0** | deg/s |
| `MC_ROLLRATE_MAX`  | 220.0 | **220.0** | deg/s |

### Multicopter Position Control
| name | defualt | tuned value | unit |
| ---  | ---     | ---         | --- |
| `MPC_LAND_ALT1` | 10.0 | 5.0 | m |
| `MPC_LAND_ALT2` | 5.0 | 2.0 | m |
| `MPC_MANTHR_MIN` | 8.0 | **8.0** | % |
| `MPC_VEL_MANUAL` | 10.0 | **10.0** | m/s |
| `MPC_XY_CRUISE` | 5.0 | **5.0** | m/s |
| `MPC_XY_VEL_MAX` | 12.0 | **12.0** | m/s |
| `MPC_Z_P` | 1.0 | **1.0** | - |
| `MPC_Z_VEL_MAX_DN` | 1.0 | **1.0** | m/s |
| `MPC_Z_VEL_MAX_UP` | 3.0 | **3.0** | m/s |


### Multicopter Rate Control
| name | default | tuned value | unit |
| ---  | ---     | ---         | ---  |
| `MC_PITCHRATE_I` | 0.2 | **0.2** | - |
| `MC_ROLLRATE_I` | 0.2 | **0.2** | - |


### Sensors
| name | default | tuned value | unit |
| ---  | ---     | ---         | ---  |
| `SENS_BOARD_X_OFF` | - | **-0.083** | - |
| `SENS_BOARD_Y_OFF` | - | **0.332** | - |
| `SENS_BOARD_Z_OFF` | - | - | - |



