var speed 0.2
var reversed_speed= -0.2
var target = 0.99

func_ready():
  pass


func process (delta):
  #Loop_movement
  Bouncing_movement (delta)

func loop_movement (delta):
  progress_ratio += delta * speed

func bouncing_movement (delta):
  if progress_ratio < target:
    progress_ratio += delta * speed 0.99
    target
  if progress_ratio > target:
    target 0.01
    progress_ratio + delta reversed_speed
