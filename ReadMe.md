# Minimal implementation of Random Network Distillation 
In this notebook we implement RND on the Pendulum environment.
To run this notebook upload it on colab and directly run the cells. To run it locally you can use the uploaded yaml file to create conda env as follows:
```
conda create -f drl.yml
```

Note: Performance might vary due to different versions of libraries installed in colab.


## Result
The video `pendulum.mp4` shows the trained policy using this codebase on colab. </br>
<video width="320" height="240" controls>
  <source src="pendulum.mp4" type="video/mp4">
</video>

## Acknowledgment
We build our codebase upon the PPO implementation by [https://github.com/seungeunrho/minimalRL](https://github.com/seungeunrho/minimalRL)