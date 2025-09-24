# C Vec3 Operations

A set of operations on a vec3 struct with doubles x, y, and z.

- **vec3Add** - adds the elements of two vec3s
- **vec3Sub** - subtracts the elements of two vec3s

- **vec3Scale** - multiplies each element of a vec3 by a scalar
- **vec3Div**   - divides (multiplies by 1.0 / scalar) each element of a vec3 by a scalar

- **vec3Hadamard** - multiplies each element of a vec3 component-wise

- **vec3Dot**   - computes the dot product of two vec3s
- **vec3Cross** - computes the cross product of 2 vec3s

- **vec3LengthSquared** - computes the length (magnitude) of a vec3 before square-rooting it
- **vec3Length**        - computes the full length of a vec3

- **vec3Normalize** - normalizes a vec3 (so that its length is 1.0)

- **vec3Reflect** - computes the reflection of a vec3 on a surface normal

- **vec3Lerp** - (linear interpolate) computes the percetage (t) of a vec3 between the tips of two vec3s
