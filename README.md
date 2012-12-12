warp
====

WARP - Work environment Automatic Rebuild Process

|partition | Read Speed| Rsync backup | Encryption | Intense writing | Per Distro | Drive type |
|----------| ----------| -------------| ---------- | --------------- |----------- | ---------- |
|   /usr   |     YES   |    NO        |  NO        |    NO           |  YES       |  SSD       |
|   /tmp   |     ?     |    NO        |  ?         |    YES          |  NO        |  HDD       |
|   /home  |     YES   |    YES       |  YES       |     ?           |  NO        |  SSD       |
|   /var   |     NO    |    NO        |  NO        |     YES         |  NO        |  HDD       |
|   /opt   |     NO    |    NO        |  NO        |     NO          |  NO        |  HDD       |
|   /boot  |     NO    |    NO        |  NO        |     NO          |  NO        |  HDD       |
|   /      |     NO    |    NO        |  NO        |     NO          |  YES       |  HDD       |
|   /mnt/movies| NO    |    ?         |  NO        |     NO          |  NO        |  HDD       |
|   /mnt/photos| NO    |    YES       |  ?         |      NO         |  NO        |  HDD       |
