action-bounds: [[-0.34906585 -0.66322512 -2.18166156  0.         -1.48352986 -0.66322512
  -2.44346095 -2.44346095 -2.7925268  -0.34906585 -0.38397244 -2.18166156
   0.         -1.48352986 -0.66322512 -2.44346095  0.         -2.7925268 ]
 [ 0.34906585  0.38397244  0.68067841  2.35619449  1.48352986  0.66322512
   2.44346095  0.          0.          0.34906585  0.66322512  0.68067841
   2.35619449  1.48352986  0.66322512  2.44346095  2.44346095  0.        ]]
max-path-num: 20
render-eval: False
prioritized-exp-replay: True
critic-activation-fn: ['relu', 'relu', 'None']
LLC-frequency: 500
loss-output-diff-coeff: 0
interpolation: False
expert-index: None
epoch-step-num: 5000000
n-step: 1
replay-buffer-size: 1000000
max-step-num: 2500000000
env-id: HumanoidBalanceFilter-v0
loss-entropy-coeff: 0.0
Physics-frequency: 1000
gating-index: None
loss-output-bound-coeff: 0.0
replay-ratio: 1
total-step-num: 2500000000
tau: 0.001
imitation-weight: 1.0
actor-l2-reg: 0.0003
max-train-time: 5
train-step-num: 1
max-episode-num: 5000000
actor-action-joints: ['right_hip_yaw', 'right_hip_roll', 'right_hip_pitch', 'right_knee', 'right_ankle_pitch', 'right_ankle_roll', 'right_shoulder_pitch', 'right_shoulder_roll', 'right_elbow', 'left_hip_yaw', 'left_hip_roll', 'left_hip_pitch', 'left_knee', 'left_ankle_pitch', 'left_ankle_roll', 'left_shoulder_pitch', 'left_shoulder_roll', 'left_elbow']
gamma: 0.995
squash-action: True
actor-activation-fn: ['relu', 'relu', 'None']
gating-activation-fn: ['relu', 'relu', 'None']
epoch-num: 500
record-start-size: 10000.0
bullet-default-PD: False
actor-lr: 0.0003
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
batch-size: 128
controlled-joints: ['right_hip_yaw', 'right_hip_roll', 'right_hip_pitch', 'right_knee', 'right_ankle_pitch', 'right_ankle_roll', 'right_shoulder_pitch', 'right_shoulder_roll', 'right_elbow', 'left_hip_yaw', 'left_hip_roll', 'left_hip_pitch', 'left_knee', 'left_ankle_pitch', 'left_ankle_roll', 'left_shoulder_pitch', 'left_shoulder_roll', 'left_elbow']
actor-weight-decay: 1e-06
actor-layer-size: [256, 256]
replay-start-size: 10000
critic-l2-reg: 0.0003
loss-output-smooth-coeff: 1.0
filter-action: True
gating-layer-size: [32, 32]
action-dim: 18
critic-lr: 0.0003
HLC-frequency: 25
state-dim: 24
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
test-num: 4
reward-scale: 0.1
critic-weight-decay: 1e-06
critic-layer-size: [256, 256]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
expert-num: 4
rollout-step-num: 1
joint-interpolation: True
task-weight: 0.0
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
filter-torque: False
max-path-step: 5000
max-test-time: 10
