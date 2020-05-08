max-train-time: 5
actor-weight-decay: 1e-06
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
squash-action: True
filter-action: True
test-num: 4
joint-interpolation: True
critic-activation-fn: ['relu', 'relu', 'None']
epoch-step-num: 5000000
max-test-time: 10
reward-scale: 0.1
gating-layer-size: [32, 32]
total-step-num: 2500000000
replay-ratio: 1
loss-output-smooth-coeff: 1.0
actor-l2-reg: 0.0003
max-path-num: 20
HLC-frequency: 25
loss-output-bound-coeff: 0.0
action-dim: 23
actor-activation-fn: ['relu', 'relu', 'None']
gating-index: None
Physics-frequency: 1000
imitation-weight: 1.0
state-dim: 29
n-step: 1
bullet-default-PD: False
critic-l2-reg: 0.0003
loss-output-diff-coeff: 0
batch-size: 128
env-id: HumanoidBalanceFilter-v0
interpolation: False
loss-entropy-coeff: 0.0
controlled-joints: ['torsoYaw', 'torsoPitch', 'torsoRoll', 'rightShoulderPitch', 'rightShoulderRoll', 'rightShoulderYaw', 'rightElbowPitch', 'leftShoulderPitch', 'leftShoulderRoll', 'leftShoulderYaw', 'leftElbowPitch', 'rightHipYaw', 'rightHipRoll', 'rightHipPitch', 'rightKneePitch', 'rightAnklePitch', 'rightAnkleRoll', 'leftHipYaw', 'leftHipRoll', 'leftHipPitch', 'leftKneePitch', 'leftAnklePitch', 'leftAnkleRoll']
action-bounds: [[-1.181  -0.13   -0.23   -2.85   -1.266  -3.1    -0.12   -2.85   -1.519
  -3.1    -2.174  -1.1    -0.5515 -2.42   -0.083  -1.4    -0.4    -0.4141
  -0.467  -2.42   -0.083  -1.4    -0.4   ]
 [ 1.181   0.67    0.23    2.      1.519   2.18    2.174   2.      1.266
   2.18    0.12    0.4141  0.467   1.619   2.86    0.78    0.4     1.1
   0.5515  1.619   2.86    0.78    0.4   ]]
filter-torque: False
actor-action-joints: ['torsoYaw', 'torsoPitch', 'torsoRoll', 'rightShoulderPitch', 'rightShoulderRoll', 'rightShoulderYaw', 'rightElbowPitch', 'leftShoulderPitch', 'leftShoulderRoll', 'leftShoulderYaw', 'leftElbowPitch', 'rightHipYaw', 'rightHipRoll', 'rightHipPitch', 'rightKneePitch', 'rightAnklePitch', 'rightAnkleRoll', 'leftHipYaw', 'leftHipRoll', 'leftHipPitch', 'leftKneePitch', 'leftAnklePitch', 'leftAnkleRoll']
actor-lr: 0.0003
expert-num: 4
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.
  -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.
   1.  1.  1.  1.  1.]]
LLC-frequency: 500
gating-activation-fn: ['relu', 'relu', 'None']
prioritized-exp-replay: True
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
rollout-step-num: 1
max-step-num: 2500000000
replay-buffer-size: 1000000
tau: 0.001
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-layer-size: [256, 256]
critic-layer-size: [256, 256]
render-eval: False
epoch-num: 500
max-path-step: 5000
record-start-size: 10000.0
gamma: 0.995
task-weight: 0.0
critic-weight-decay: 1e-06
expert-index: None
max-episode-num: 5000000
critic-lr: 0.0003
train-step-num: 1
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
replay-start-size: 10000
