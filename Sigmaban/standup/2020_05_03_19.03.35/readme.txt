replay-start-size: 10000
train-step-num: 1
max-step-num: 2500000000
Physics-frequency: 1000
gating-layer-size: [32, 32]
bullet-default-PD: False
reward-scale: 0.1
gating-activation-fn: ['relu', 'relu', 'None']
actor-layer-size: [256, 256]
max-path-step: 5000
max-path-num: 20
render-eval: False
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
env-id: HumanoidBalanceFilter-v0
critic-lr: 0.0003
HLC-frequency: 25
tau: 0.001
test-num: 4
actor-weight-decay: 1e-06
gating-index: None
critic-weight-decay: 1e-06
max-episode-num: 5000000
n-step: 1
replay-buffer-size: 1000000
loss-entropy-coeff: 0.0
prioritized-exp-replay: True
filter-torque: False
total-step-num: 2500000000
critic-activation-fn: ['relu', 'relu', 'None']
max-train-time: 5
action-bounds: [[-0.34906585 -0.66322512 -2.18166156  0.         -1.48352986 -0.66322512
  -2.44346095 -2.44346095 -2.7925268  -0.34906585 -0.38397244 -2.18166156
   0.         -1.48352986 -0.66322512 -2.44346095  0.         -2.7925268 ]
 [ 0.34906585  0.38397244  0.68067841  2.35619449  1.48352986  0.66322512
   2.44346095  0.          0.          0.34906585  0.66322512  0.68067841
   2.35619449  1.48352986  0.66322512  2.44346095  2.44346095  0.        ]]
gamma: 0.995
imitation-weight: 1.0
actor-action-joints: ['right_hip_yaw', 'right_hip_roll', 'right_hip_pitch', 'right_knee', 'right_ankle_pitch', 'right_ankle_roll', 'right_shoulder_pitch', 'right_shoulder_roll', 'right_elbow', 'left_hip_yaw', 'left_hip_roll', 'left_hip_pitch', 'left_knee', 'left_ankle_pitch', 'left_ankle_roll', 'left_shoulder_pitch', 'left_shoulder_roll', 'left_elbow']
state-dim: 24
epoch-num: 500
expert-index: None
replay-ratio: 1
loss-output-bound-coeff: 0.0
LLC-frequency: 500
actor-l2-reg: 0.0003
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
loss-output-diff-coeff: 0
max-test-time: 10
filter-action: True
batch-size: 128
controlled-joints: ['right_hip_yaw', 'right_hip_roll', 'right_hip_pitch', 'right_knee', 'right_ankle_pitch', 'right_ankle_roll', 'right_shoulder_pitch', 'right_shoulder_roll', 'right_elbow', 'left_hip_yaw', 'left_hip_roll', 'left_hip_pitch', 'left_knee', 'left_ankle_pitch', 'left_ankle_roll', 'left_shoulder_pitch', 'left_shoulder_roll', 'left_elbow']
joint-interpolation: True
epoch-step-num: 5000000
record-start-size: 10000.0
squash-action: True
critic-l2-reg: 0.0003
rollout-step-num: 1
expert-num: 4
task-weight: 0.0
actor-activation-fn: ['relu', 'relu', 'None']
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-lr: 0.0003
interpolation: False
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-dim: 18
loss-output-smooth-coeff: 1.0
critic-layer-size: [256, 256]
