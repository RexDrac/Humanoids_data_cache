controlled-joints: ['right_hip_yaw', 'right_hip_roll', 'right_hip_pitch', 'right_knee', 'right_ankle_pitch', 'right_ankle_roll', 'right_shoulder_pitch', 'right_shoulder_roll', 'right_elbow', 'left_hip_yaw', 'left_hip_roll', 'left_hip_pitch', 'left_knee', 'left_ankle_pitch', 'left_ankle_roll', 'left_shoulder_pitch', 'left_shoulder_roll', 'left_elbow']
replay-start-size: 10000
critic-weight-decay: 1e-06
reward-scale: 0.1
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
expert-index: None
epoch-num: 500
train-step-num: 1
critic-layer-size: [256, 256]
replay-buffer-size: 1000000
state-dim: 24
actor-action-joints: ['right_hip_yaw', 'right_hip_roll', 'right_hip_pitch', 'right_knee', 'right_ankle_pitch', 'right_ankle_roll', 'right_shoulder_pitch', 'right_shoulder_roll', 'right_elbow', 'left_hip_yaw', 'left_hip_roll', 'left_hip_pitch', 'left_knee', 'left_ankle_pitch', 'left_ankle_roll', 'left_shoulder_pitch', 'left_shoulder_roll', 'left_elbow']
epoch-step-num: 5000000
gating-index: None
filter-action: True
max-path-num: 20
LLC-frequency: 500
Physics-frequency: 1000
joint-interpolation: True
record-start-size: 10000.0
expert-num: 4
batch-size: 128
actor-weight-decay: 1e-06
replay-ratio: 1
total-step-num: 2500000000
max-episode-num: 5000000
test-num: 4
max-path-step: 5000
actor-lr: 0.0003
loss-output-smooth-coeff: 1.0
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
prioritized-exp-replay: True
action-bounds: [[-0.34906585 -0.66322512 -2.18166156  0.         -1.48352986 -0.66322512
  -2.44346095 -2.44346095 -2.7925268  -0.34906585 -0.38397244 -2.18166156
   0.         -1.48352986 -0.66322512 -2.44346095  0.         -2.7925268 ]
 [ 0.34906585  0.38397244  0.68067841  2.35619449  1.48352986  0.66322512
   2.44346095  0.          0.          0.34906585  0.66322512  0.68067841
   2.35619449  1.48352986  0.66322512  2.44346095  2.44346095  0.        ]]
env-id: HumanoidBalanceFilter-v0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
rollout-step-num: 1
critic-lr: 0.0003
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
filter-torque: False
gating-activation-fn: ['relu', 'relu', 'None']
n-step: 1
bullet-default-PD: False
gamma: 0.995
max-step-num: 2500000000
squash-action: True
imitation-weight: 1.0
critic-l2-reg: 0.0003
max-test-time: 10
action-dim: 18
loss-output-bound-coeff: 0.0
loss-entropy-coeff: 0.0
HLC-frequency: 25
actor-l2-reg: 0.0003
tau: 0.001
interpolation: False
task-weight: 0.0
loss-output-diff-coeff: 0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-activation-fn: ['relu', 'relu', 'None']
actor-activation-fn: ['relu', 'relu', 'None']
gating-layer-size: [32, 32]
actor-layer-size: [256, 256]
render-eval: False
max-train-time: 5
