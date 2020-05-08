max-step-num: 2500000000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-weight-decay: 1e-06
controlled-joints: ['right_hip_yaw', 'right_hip_roll', 'right_hip_pitch', 'right_knee', 'right_ankle_pitch', 'right_ankle_roll', 'right_shoulder_pitch', 'right_shoulder_roll', 'right_elbow', 'left_hip_yaw', 'left_hip_roll', 'left_hip_pitch', 'left_knee', 'left_ankle_pitch', 'left_ankle_roll', 'left_shoulder_pitch', 'left_shoulder_roll', 'left_elbow']
actor-lr: 0.0003
interpolation: False
expert-num: 4
critic-l2-reg: 0.0003
render-eval: False
actor-action-joints: ['right_hip_yaw', 'right_hip_roll', 'right_hip_pitch', 'right_knee', 'right_ankle_pitch', 'right_ankle_roll', 'right_shoulder_pitch', 'right_shoulder_roll', 'right_elbow', 'left_hip_yaw', 'left_hip_roll', 'left_hip_pitch', 'left_knee', 'left_ankle_pitch', 'left_ankle_roll', 'left_shoulder_pitch', 'left_shoulder_roll', 'left_elbow']
total-step-num: 2500000000
max-path-num: 20
task-weight: 0.0
Physics-frequency: 1000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
replay-start-size: 10000
critic-activation-fn: ['relu', 'relu', 'None']
max-test-time: 10
joint-interpolation: True
critic-layer-size: [256, 256]
actor-l2-reg: 0.0003
tau: 0.001
gating-index: None
action-bounds: [[-0.34906585 -0.66322512 -2.18166156  0.         -1.48352986 -0.66322512
  -2.44346095 -2.44346095 -2.7925268  -0.34906585 -0.38397244 -2.18166156
   0.         -1.48352986 -0.66322512 -2.44346095  0.         -2.7925268 ]
 [ 0.34906585  0.38397244  0.68067841  2.35619449  1.48352986  0.66322512
   2.44346095  0.          0.          0.34906585  0.66322512  0.68067841
   2.35619449  1.48352986  0.66322512  2.44346095  2.44346095  0.        ]]
train-step-num: 1
record-start-size: 10000.0
actor-weight-decay: 1e-06
loss-output-smooth-coeff: 1.0
bullet-default-PD: False
epoch-step-num: 5000000
filter-torque: False
n-step: 1
loss-entropy-coeff: 0.0
gating-activation-fn: ['relu', 'relu', 'None']
batch-size: 128
imitation-weight: 1.0
action-dim: 18
max-train-time: 5
state-dim: 24
filter-action: True
expert-index: None
test-num: 4
rollout-step-num: 1
gating-layer-size: [32, 32]
HLC-frequency: 25
actor-activation-fn: ['relu', 'relu', 'None']
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
prioritized-exp-replay: True
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
replay-buffer-size: 1000000
max-path-step: 5000
env-id: HumanoidBalanceFilter-v0
loss-output-diff-coeff: 0
epoch-num: 500
actor-layer-size: [256, 256]
replay-ratio: 1
critic-lr: 0.0003
loss-output-bound-coeff: 0.0
squash-action: True
LLC-frequency: 500
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-episode-num: 5000000
reward-scale: 0.1
gamma: 0.995
