mc_rtc_ros
==========

[![License](https://img.shields.io/badge/License-BSD%202--Clause-green.svg)](https://opensource.org/licenses/BSD-2-Clause)

This ROS stack aims at providing various tools to use along mc_rtc.

## Current list of tools

- **mc_convex_visualization** allows to publish the convex hulls of a robot as a polygon message that can be visualized in RViz
- **mc_log_visualization** is a tool to visualize logs generated by an mc_rtc controller
- **mc_rtc_rviz_panel** is an mc_rtc's GUI client that can be used inside RViZ
- **mc_rtc_ticker** provides an RViz interface to mc_rtc
- **mc_surfaces_visualization** allows to visualize a robot's surfaces within RViZ

## Dependencies

This stack requires:
- [mc_rtc](https://gite.lirmm.fr/multi-contact/mc_rtc)
- [mc_rtc_ros_data](https://gite.lirmm.fr/multi-contact/mc_rtc_ros_data)
- [Qt](https://www.qt.io/): if building with ROS and RViz then the versions that RViZ was built with otherwise Qt4/Qt5
- [QWT](https://qwt.sourceforge.io/)
