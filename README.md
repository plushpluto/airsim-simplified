# airsim-simplified

This is a playground for AirSim. The primary purpose for this repo is to avoid the unnecessary files that the original repo has, thereby giving a clear understanding of AirSim. Docker containers are placed from the original AirSim repo to create a simplified version for any user to get started with AirSim. Going forward, I am planning to put scripts and environments for anyone who is interested. Currently, there are two folders; docker and python. You can use the docker containers to get the environment and the server up and running. The python scripts are to play around with the drones or cars.

Hardware requirements: (Taken from the original repo)

We recommend GPUs such as NVidia 1080 or NVidia Titan series with powerful desktop such as one with 64GB RAM, 6+ cores, SSDs and 2-3 displays (ideally 4K). We have found HP Z840 work quite well for our needs. The development experience on high-end laptops is generally sub-par compared to powerful desktops however they might be useful in a pinch. You generally want laptops with discrete NVidia GPU (at least M2000 or better) with 64GB RAM, SSDs and hopefully 4K display. We have found models such as Lenovo P50 work well for our needs. Laptops with only integrated graphics might not work well.

Get started:
1. Install docker.
2. Install nvidia-docker2.
3. Install anaconda (python3) and create an environment "airsim" to tidy up things.
4. pip3 install msgpack-rpc-python and pip3 install airsim inside the newly created "airsim" environment.
5. Just play around with the repo. Enjoy.

Original repo: https://github.com/microsoft/AirSim

