# Mechatronic Gripper Digital Twin Bundle

This repository is intended as a starting point for integrating SCHUNK mechatronic grippers into simulation workflows and digital twin applications.

It collects pointers to the assets, drivers, and tooling needed to simulate SCHUNK grippers, control the real hardware, and eventually connect both sides in real-to-sim and sim-to-real workflows.

## Related Repositories

- [SCHUNK mechatronic gripper assets](https://github.com/SCHUNK-SE-Co-KG/schunk_mechatronic_gripper_assets)  
	Contains URDF and USD assets for SCHUNK mechatronic grippers. The USD files can be used with NVIDIA Isaac Sim, while the URDF files can be used with other robotics simulation environments.

- [SCHUNK mechatronic gripper ROS 2 driver](https://github.com/SCHUNK-SE-Co-KG/schunk_mechatronic_gripper)  
	Provides the ROS 2 driver for controlling SCHUNK mechatronic grippers such as EGU, EGK, and EZU devices.

- [SCHUNK mechatronic gripper MCP server](https://github.com/SCHUNK-SE-Co-KG/schunk_mechatronic_gripper_mcp_server)  
	Provides an MCP server for the ROS 2 driver, enabling MCP-compatible clients to interact with and control SCHUNK EGU, EGK, and EZU grippers.

## Planned Examples

In the future, this repository will contain example workflows that show how to use these components together, including:

- controlling a SCHUNK mechatronic gripper in Isaac Sim
- integrating gripper assets into simulation scenes
- using feedback from the real gripper to adapt the simulation flow
- building real-to-sim and sim-to-real workflows around SCHUNK mechatronic grippers

## License

This project is licensed under the GNU General Public License version 3. See [LICENSE](LICENSE) for details.

