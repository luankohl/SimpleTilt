# SimpleTilt.js

A simple javascript plugin to do tilt effect.

![SimpleTilt.js demo gif](https://raw.githubusercontent.com/luankohl/SimpleTilt/master/simpletilt.gif)

### Usage

```html
<!DOCTYPE html>
<body>
  <div class="your-class">
    <!-- If fx3d option is enabled, you need to insert fx3d class in children to works correctly -->
    <div class="children fx3d"></div>
  </div>
  <!-- Your Tilt element -->
  <script src="SimpleTilt.js"></script>
  <!-- Load SimpleTilt.js -->
  <!-- Active SimpleTilt in your elements -->
  <script>
    tilter(".your-class", {
      perspective: 300, // Default 400
      maxTilt: 4, // Default 4
      mantain: false, // Default false
      fx3d: true, // Default false
      fxDistance: 70, // Default 40
    });
  </script>
</body>
```

### Options

```js
perspective:    400, // Transform perspective, the lower the more extreme the tilt gets.
maxTilt:        4, // Size of tilt.
mantain:        false, // Mantain tilt after mouse leave.
fx3d:           1, // Tilt children elements
fxDistance:     40, // Distance of children elements on the Z axis - Use transform: translateZ(40);
```
