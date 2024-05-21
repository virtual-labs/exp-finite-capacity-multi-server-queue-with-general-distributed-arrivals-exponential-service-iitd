To perform the experiment accurately, follow these detailed steps sequentially:

1. **Simulation Setup:**
   - **Select the Arrival Time Distribution:** Begin by choosing the distribution that describes the inter-arrival times of customers (e.g., exponential, uniform, etc.).
   - **Set Parameter Values:**
     - **Mean Arrival Rate:** Specify the average rate at which customers arrive at the system.
     - **Mean Service Rate:** Define the average rate at which servers can complete service.
     - **Number of Servers:** Indicate the total number of servers available in the system.
   - These steps are crucial to accurately simulate the GI/M/c/N queueing model, where GI denotes a general independent arrival time distribution, M represents an exponential service time distribution, c is the number of servers, and N is the system capacity.

2. **Stability Check:**
   - Ensure that the mean arrival rate is less than the product of the mean service rate and the number of servers (\(\lambda < c \mu\)). This condition is essential for achieving a steady-state solution, where the system reaches equilibrium and metrics such as queue length and waiting time become stable over time.

3. **System Capacity Configuration:**
   - Set the maximum number of customers (N) that the system can handle, including those being served and those waiting in the queue. This parameter defines the capacity limit of the system and prevents overloading.

4. **Initiating the Experiment:**
   - Click the 'Start' button to launch the simulation. This action begins the process based on the parameters set in the previous steps, allowing the system to process arrivals and services.

5. **Monitoring and Stopping the Experiment:**
   - Observe the simulation as it runs. You can monitor various performance indicators such as queue length, server utilization, and waiting times.
   - When sufficient data is collected or the desired simulation time is reached, click the 'Stop' button to halt the experiment. This action will finalize the simulation and allow you to view the results.

6. **Analyzing Results:**
   - After stopping the experiment, review the steady-state results both numerically (e.g., average queue length, average waiting time) and graphically (e.g., time-series plots, histograms).
   - Compare these experimental results with theoretical predictions to evaluate the accuracy of the model and the simulation. This comparison helps validate the assumptions and parameters used and can provide insights into system performance and potential improvements.

