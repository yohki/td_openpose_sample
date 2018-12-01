# td_openpose_sample
Sample .toe file using OpenPose on TouchDesigner

- Requires [Python API of OpenPose](https://github.com/CMU-Perceptual-Computing-Lab/openpose/blob/master/doc/installation.md#python-api)
- Need to change path values written in OP Execute DAT script:

```python:
sys.path.append('D:/openpose/build/python/openpose')
```

```python:
params["default_model_folder"] = "D:/openpose/models/"
```
