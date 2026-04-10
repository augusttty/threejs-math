# threejs-math-with-types
Stand-alone TypeScript version of three.js math. (Forked from [ros2jsguy/threejs-math](https://github.com/ros2jsguy/threejs-math), with type export fixes)
This package is a standalone version of [three.js (r147) math](https://threejs.org/docs/#api/en/math/Box2) classes with TypeScript support and integrated TSdoc documentation. 

* Box2
* Box3
* Color
* Cylindrical
* Euler
* Interpolant
  * CubicInterpolant
  * DiscreteInterpolant
  * LinearInterpolant
  * QuaternionInterpolant
* Line3
* MathUtils
* Matrix (interface)
* Matrix3
* Matrix4
* Plane
* Quaternion
* Ray
* Sphere
* Spherical
* Triangle
* Vector (interface)
* Vector2
* Vector3
* Vector4

# API Documentation
The classes in TSDoc format are available in the `docs/` directory after running `npm run build:docs`.

# History
This module started as a fork of [three-math-ts](https://github.com/chenhebing/three.math) which has been dormant for some time. It was then extended by [ros2jsguy/threejs-math](https://github.com/ros2jsguy/threejs-math). This package (`threejs-math-with-types`) further fixes type export issues.

