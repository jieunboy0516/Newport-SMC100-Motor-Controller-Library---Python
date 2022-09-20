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

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.

