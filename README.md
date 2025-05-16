# Learning-Driven-Dispatching-and-Routing-Optimization-for-AGVs-in-Stochastic-Warehouse-Systems-
ENPM692 FINAL PROJECT


### ACTION SPACE 

In this simulation our robots are having following discrete action space
       
        AGVs = {Shelf Locations, Goal Locations}
        Action Space (The Picker Robots) = {Goal and Shelf Locations}


#### 2D Layout of the Warehouse
<img width="619" alt="Screenshot 2025-05-15 at 11 14 55 PM" src="https://github.com/user-attachments/assets/0be3cb27-c881-44e2-8e23-81ce9a19dbed" />

### Installation


       git clone gh repo clone IshanMahesh/Learning-Driven-Dispatching-and-Routing-Optimization-for-AGVs-in-Stochastic-Warehouse-Systems-
       cd Learning-Driven-Dispatching-and-Routing-Optimization-for-AGVs-in-Stochastic-Warehouse-Systems-
       pip install -e .



       pip install tarware
       pip install gymnasium 
       gymnasium --version


### Running


       python scripts/run_heuristic.py --num_episodes=10000 --seed=0 --render


       



#### Simulation (Realtime)
![Screenshot 2025-05-15 at 9 51 35 PM](https://github.com/user-attachments/assets/dfe16914-e6e0-42fe-b876-5e60902d1d3c)
