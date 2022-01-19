# N_body_task

Here we make spacecraft motion modelling in N body framework. Now N = 3, but we can easily add new bodies in the model.
Firstly, we connect to JPL HORIZONS system to dowload precise data (e.g. Earth and Moon motion):

![Earth_Moon](https://user-images.githubusercontent.com/67582707/150093722-75fd04b9-485f-4266-8fd4-27d02284f05e.gif)

Then we solve ODE system for spacecraft motion modelling (only gravity forces):

![ezgif com-gif-maker (2)](https://user-images.githubusercontent.com/67582707/150093985-916423da-45b9-4939-ae98-82865deaeb43.gif)

Afterwards other planets, forces and control program will be added.
