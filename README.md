# Newport-SMC100-Motor-Controller-Library---Python
A python Library created to control the Newport SMC100 motor 




Most codes are from:
https://github.com/silky/qy/blob/master/hardware/smc100.py

My part is just to update the code as the code there is deprecated.

I also added few features.

Refer to the manual yourself to add the features you want:
https://www.newport.com/medias/sys_master/images/images/h8d/h3a/8797263101982/SMC100CC-SMC100PP-User-Manual.pdf
## Main API References
### Only few funcions are documented. Read the source code and the manual if needed.

#### Move

```python
  move_absolute(controller, position)
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
|`controller` | `string` | **Required**. Your motor number (usually 1) |
| `position ` | `string` | **Required**. position to move to between 0-27|

#### Get item

```python
  reset(controller)
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `controller`      | `string` | **Required**. Your motor number (usually 1) |

#### move_relative(controller, position)

Is like move_absolute() but is in moving in relative position

