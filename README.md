# pairwise-camera-collision-spring

## 领域

游戏、图形与多媒体

## 主题

摄像机弹簧臂碰撞

## 说明

球形扫掠、近裁剪采样与瞬移对齐。

初始状态下 `gameplay/camera_collision_spring.py` 中所有函数抛出 `NotImplementedError`，测试全部失败。
修复实现后运行：

```bash
python -m pytest -q
```

期望全部通过。
