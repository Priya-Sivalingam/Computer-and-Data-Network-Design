# Computer and Data Network Design

## Objective
Design a computer network for IT Centre and Department blocks using a 3-tier network model (core, distribution, access).
![image](https://github.com/user-attachments/assets/1ad1cb7d-5752-4abc-8c8c-7f2e69dde9db)

## Network Overview
### IT Centre Block
- **Director Office**: 2 PCs
- **Network Manager Room**: 1 PC
- **2 Technical Officers Rooms**: 2 PCs
- **Staff Office**: 5 PCs
- **Meeting Room**: 2 data points + Wi-Fi
- **Computer Labs 1 & 2**: 60 PCs each
- **Digital Learning & Media Centre**: 30 PCs + 1 printer
- **Printing Room**: 2 printers
- **Lobby Area**: Wi-Fi

### Department Block
- **4 Lecture Halls**: 4 PCs + multimedia devices
- **14 Staff Rooms**: 14 PCs
- **4 Technical Officers Rooms**: 4 PCs
- **Department Meeting Room**: 2 data points + Wi-Fi
- **Computer Labs 1 & 2**: 50 PCs each
- **Network Engineering Lab**: 10 PCs
- **Microprocessor Lab**: 12 PCs
- **Computer Vision & Machine Learning Lab**: 50 PCs
- **Department Office**: 2 PCs + 1 printer

## VLAN & IP Allocation
- VLANs created for each room.
- IPs allocated using VLSM to minimize waste.

## Security Configurations
- **Router**: Password-protected (e.g., password 2020E122).
- **Printers**: Access restricted to staff VLANs.
- **ACLs**: Implemented to control network access.

## Testing
- **Ping Test**: Validate connectivity.
- **Access Control**: Ensure restricted access between VLANs.

---
