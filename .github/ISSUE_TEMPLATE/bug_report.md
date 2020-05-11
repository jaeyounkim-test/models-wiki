---
name: Bug report
about: Create a report to help us improve
title: ''
labels: ''
assignees: ''

---

**Please provide the entire URL of the model you are using?**
https://github.com/tensorflow/models/tree/master/official/...

**Describe the bug**
A clear and concise description of what the bug is.

**To Reproduce**
Steps to reproduce the behavior.

**Expected behavior**
A clear and concise description of what you expected to happen.

**Additional context**
Include any logs or source code that would be helpful to diagnose the problem.

**System information**
- OS Platform and Distribution (e.g., Linux Ubuntu 16.04):
- Mobile device (e.g., Pixel 4) if the issue happens on a mobile device:
- TensorFlow installed from (source or binary):
- TensorFlow version (use command below):
- Python version:
- Bazel version (if compiling from source):
- GCC/Compiler version (if compiling from source):
- CUDA/cuDNN version:
- GPU model and memory:

Collect system information using our environment capture script.
https://github.com/tensorflow/tensorflow/tree/master/tools/tf_env_collect.sh

You can also obtain the TensorFlow version with:

1. TensorFlow 1.0
`python -c "import tensorflow as tf; print(tf.GIT_VERSION, tf.VERSION)"`

2. TensorFlow 2.0
`python -c "import tensorflow as tf; print(tf.version.GIT_VERSION, tf.version.VERSION)"`
