LLC-frequency: 500
loss-output-bound-coeff: 0.0
gating-layer-size: [32, 32]
total-step-num: 2500000000
squash-action: True
env-id: HumanoidBalanceFilter-v0
prioritized-exp-replay: True
Physics-frequency: 1000
actor-layer-size: [256, 256]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
expert-index: None
expert-num: 4
gating-activation-fn: ['relu', 'relu', 'None']
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-path-step: 5000
max-step-num: 2500000000
filter-torque: False
tau: 0.001
critic-lr: 0.0003
actor-l2-reg: 0.0003
critic-weight-decay: 1e-06
test-num: 4
render-eval: False
loss-output-smooth-coeff: 0.5
interpolation: False
n-step: 1
rollout-step-num: 1
max-episode-num: 5000000
epoch-step-num: 5000000
filter-action: True
reward-scale: 0.1
batch-size: 128
actor-activation-fn: ['relu', 'relu', 'None']
HLC-frequency: 25
imitation-weight: 1.0
actor-weight-decay: 1e-06
action-bounds: [[-0.34906585 -0.66322512 -2.18166156  0.         -1.48352986 -0.66322512
  -2.44346095 -2.44346095 -2.7925268  -0.34906585 -0.38397244 -2.18166156
   0.         -1.48352986 -0.66322512 -2.44346095  0.         -2.7925268 ]
 [ 0.34906585  0.38397244  0.68067841  2.35619449  1.48352986  0.66322512
   2.44346095  0.          0.          0.34906585  0.66322512  0.68067841
   2.35619449  1.48352986  0.66322512  2.44346095  2.44346095  0.        ]]
loss-entropy-coeff: 0.0
loss-output-diff-coeff: 0
replay-ratio: 1
bullet-default-PD: False
critic-layer-size: [256, 256]
critic-activation-fn: ['relu', 'relu', 'None']
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
epoch-num: 500
replay-start-size: 10000
record-start-size: 10000.0
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
max-train-time: 5
state-dim: 24
replay-buffer-size: 1000000
critic-l2-reg: 0.0003
joint-interpolation: True
gating-index: None
actor-action-joints: ['right_hip_yaw', 'right_hip_roll', 'right_hip_pitch', 'right_knee', 'right_ankle_pitch', 'right_ankle_roll', 'right_shoulder_pitch', 'right_shoulder_roll', 'right_elbow', 'left_hip_yaw', 'left_hip_roll', 'left_hip_pitch', 'left_knee', 'left_ankle_pitch', 'left_ankle_roll', 'left_shoulder_pitch', 'left_shoulder_roll', 'left_elbow']
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
task-weight: 0.0
action-dim: 18
actor-lr: 0.0003
max-path-num: 20
max-test-time: 10
train-step-num: 1
controlled-joints: ['right_hip_yaw', 'right_hip_roll', 'right_hip_pitch', 'right_knee', 'right_ankle_pitch', 'right_ankle_roll', 'right_shoulder_pitch', 'right_shoulder_roll', 'right_elbow', 'left_hip_yaw', 'left_hip_roll', 'left_hip_pitch', 'left_knee', 'left_ankle_pitch', 'left_ankle_roll', 'left_shoulder_pitch', 'left_shoulder_roll', 'left_elbow']
gamma: 0.995
