# pytorch-trpo
PyTorch implementation of Vanilla Policy Gradient, Truncated Natural Policy Gradient, Trust Region Policy Optimization, Proximal Policy Optimization.
Analysis of workability of the system is in Report_PPO_Humanoid.pdf file.

# Train
* **algorithm**: PG, NPG, TRPO, PPO
* **env**: Ant-v2, HalfCheetah-v2, Hopper-v2, Humanoid-v2, HumanoidStandup-v2, InvertedPendulum-v2, Reacher-v2, Swimmer-v2, Walker2d-v2
The system trains a Humanoid-v2 env using the PPO algorithm by default. If you wanna specify other envs and algs use:
~~~
python main.py --algorithm "algorithm name" --env "environment name"
~~~

# Reference
This code is modified version of codes
* [OpenAI Baseline](https://github.com/openai/baselines/tree/master/baselines/trpo_mpi)
* [Pytorch implemetation of TRPO](https://github.com/ikostrikov/pytorch-trpo)
* [Pytorch implementation of all these algorithms which was modified](https://github.com/dnddnjs/mujoco-pg)
