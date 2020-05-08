Physics-frequency: 1000
actor-l2-reg: 0.0003
joint-interpolation: True
test-num: 4
controlled-joints: ['torsoYaw', 'torsoPitch', 'torsoRoll', 'rightShoulderPitch', 'rightShoulderRoll', 'rightShoulderYaw', 'rightElbowPitch', 'leftShoulderPitch', 'leftShoulderRoll', 'leftShoulderYaw', 'leftElbowPitch', 'rightHipYaw', 'rightHipRoll', 'rightHipPitch', 'rightKneePitch', 'rightAnklePitch', 'rightAnkleRoll', 'leftHipYaw', 'leftHipRoll', 'leftHipPitch', 'leftKneePitch', 'leftAnklePitch', 'leftAnkleRoll']
tau: 0.001
rollout-step-num: 1
critic-layer-size: [256, 256]
max-episode-num: 5000000
replay-buffer-size: 1000000
LLC-frequency: 500
imitation-weight: 1.0
max-path-step: 5000
critic-weight-decay: 1e-06
state-dim: 29
gamma: 0.995
actor-activation-fn: ['relu', 'relu', 'None']
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
replay-ratio: 1
critic-activation-fn: ['relu', 'relu', 'None']
filter-action: True
gating-activation-fn: ['relu', 'relu', 'None']
total-step-num: 2500000000
epoch-step-num: 5000000
gating-index: None
HLC-frequency: 25
action-bounds: [[-1.181  -0.13   -0.23   -2.85   -1.266  -3.1    -0.12   -2.85   -1.519
  -3.1    -2.174  -1.1    -0.5515 -2.42   -0.083  -1.4    -0.4    -0.4141
  -0.467  -2.42   -0.083  -1.4    -0.4   ]
 [ 1.181   0.67    0.23    2.      1.519   2.18    2.174   2.      1.266
   2.18    0.12    0.4141  0.467   1.619   2.86    0.78    0.4     1.1
   0.5515  1.619   2.86    0.78    0.4   ]]
max-path-num: 20
replay-start-size: 10000
render-eval: False
env-id: HumanoidBalanceFilter-v0
loss-output-diff-coeff: 0
expert-index: None
critic-l2-reg: 0.0003
expert-num: 4
max-test-time: 10
loss-output-smooth-coeff: 1.0
max-train-time: 5
interpolation: False
record-start-size: 10000.0
task-weight: 0.0
filter-torque: False
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.
  -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.
   1.  1.  1.  1.  1.]]
gating-layer-size: [32, 32]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
train-step-num: 1
batch-size: 128
prioritized-exp-replay: True
actor-lr: 0.0003
epoch-num: 500
actor-action-joints: ['torsoYaw', 'torsoPitch', 'torsoRoll', 'rightShoulderPitch', 'rightShoulderRoll', 'rightShoulderYaw', 'rightElbowPitch', 'leftShoulderPitch', 'leftShoulderRoll', 'leftShoulderYaw', 'leftElbowPitch', 'rightHipYaw', 'rightHipRoll', 'rightHipPitch', 'rightKneePitch', 'rightAnklePitch', 'rightAnkleRoll', 'leftHipYaw', 'leftHipRoll', 'leftHipPitch', 'leftKneePitch', 'leftAnklePitch', 'leftAnkleRoll']
max-step-num: 2500000000
critic-lr: 0.0003
loss-output-bound-coeff: 0.0
actor-weight-decay: 1e-06
squash-action: True
loss-entropy-coeff: 0.0
action-dim: 23
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
reward-scale: 0.1
actor-layer-size: [256, 256]
n-step: 1
bullet-default-PD: False
