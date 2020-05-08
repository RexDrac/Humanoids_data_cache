action-dim: 23
filter-action: True
task-weight: 0.0
gating-index: None
reward-scale: 0.1
train-step-num: 1
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.
  -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.
   1.  1.  1.  1.  1.]]
gating-layer-size: [32, 32]
replay-buffer-size: 1000000
actor-weight-decay: 1e-06
batch-size: 128
critic-lr: 0.0003
controlled-joints: ['torsoYaw', 'torsoPitch', 'torsoRoll', 'rightShoulderPitch', 'rightShoulderRoll', 'rightShoulderYaw', 'rightElbowPitch', 'leftShoulderPitch', 'leftShoulderRoll', 'leftShoulderYaw', 'leftElbowPitch', 'rightHipYaw', 'rightHipRoll', 'rightHipPitch', 'rightKneePitch', 'rightAnklePitch', 'rightAnkleRoll', 'leftHipYaw', 'leftHipRoll', 'leftHipPitch', 'leftKneePitch', 'leftAnklePitch', 'leftAnkleRoll']
gamma: 0.995
actor-l2-reg: 0.0003
gating-activation-fn: ['relu', 'relu', 'None']
actor-activation-fn: ['relu', 'relu', 'None']
actor-lr: 0.0003
max-path-step: 5000
loss-output-diff-coeff: 0
loss-entropy-coeff: 0.0
joint-interpolation: True
env-id: HumanoidBalanceFilter-v0
LLC-frequency: 500
test-num: 4
expert-num: 4
rollout-step-num: 1
expert-index: None
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
prioritized-exp-replay: True
critic-layer-size: [256, 256]
render-eval: False
actor-layer-size: [256, 256]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
critic-weight-decay: 1e-06
state-dim: 29
HLC-frequency: 25
max-step-num: 2500000000
critic-l2-reg: 0.0003
critic-activation-fn: ['relu', 'relu', 'None']
filter-torque: False
max-path-num: 20
actor-action-joints: ['torsoYaw', 'torsoPitch', 'torsoRoll', 'rightShoulderPitch', 'rightShoulderRoll', 'rightShoulderYaw', 'rightElbowPitch', 'leftShoulderPitch', 'leftShoulderRoll', 'leftShoulderYaw', 'leftElbowPitch', 'rightHipYaw', 'rightHipRoll', 'rightHipPitch', 'rightKneePitch', 'rightAnklePitch', 'rightAnkleRoll', 'leftHipYaw', 'leftHipRoll', 'leftHipPitch', 'leftKneePitch', 'leftAnklePitch', 'leftAnkleRoll']
imitation-weight: 1.0
max-train-time: 5
n-step: 1
record-start-size: 10000.0
action-bounds: [[-1.181  -0.13   -0.23   -2.85   -1.266  -3.1    -0.12   -2.85   -1.519
  -3.1    -2.174  -1.1    -0.5515 -2.42   -0.083  -1.4    -0.4    -0.4141
  -0.467  -2.42   -0.083  -1.4    -0.4   ]
 [ 1.181   0.67    0.23    2.      1.519   2.18    2.174   2.      1.266
   2.18    0.12    0.4141  0.467   1.619   2.86    0.78    0.4     1.1
   0.5515  1.619   2.86    0.78    0.4   ]]
max-test-time: 10
epoch-step-num: 5000000
loss-output-bound-coeff: 0.0
total-step-num: 2500000000
replay-ratio: 1
loss-output-smooth-coeff: 1.0
tau: 0.001
epoch-num: 500
squash-action: True
replay-start-size: 10000
Physics-frequency: 1000
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-episode-num: 5000000
bullet-default-PD: False
interpolation: False
