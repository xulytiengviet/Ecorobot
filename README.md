# EcoRobot — 3D Engineering Studio

**Author:** Long Ngo · 2026 · MIT

A browser-based animated conceptual 3D reconstruction of an aquatic vegetation and river trash collection vessel based on user-provided photographs.

## Features
- Full 3D navigable Three.js/WebGL scene, cabin, pontoons, debris hold, articulated inclined intake conveyor, moving belt slats, support arms, rails and simulated water motion.
- Motion controls: raise/lower conveyor, conveyor speed, vessel speed, water level; animation play/pause and reset.
- Perspective, top and side cameras; explode view, component visibility, wireframe, PNG capture and binary GLB export.
- Responsive Vietnamese engineering dashboard, statically hosted on GitHub Pages.

## Run
Open `index.html` through an HTTP static server or deploy via GitHub Pages. The application loads Three.js ES modules through jsDelivr, so internet access is required.

## Important limitations
This is a **visual kinematic simulation**, not reverse-engineered manufacturer CAD. Vessel sizes and mechanical ratios are conceptual. No structural, hydraulic, stability, collision or hydrodynamic certification is implied. No physical debris-collection efficiency or safe-control claims. Independent marine engineering and safety reviews are required before fabrication. No reference images or third-party logos are included in the published code.

## Next steps
Engineering measurements → detailed GLB/Blender assets → validated conveyor dynamics → ROS 2/Gazebo testing → ViRustGIS digital twin missions.

## License
MIT for original code; third-party dependencies retain their own licenses.