# Spare Parts Logistics Optimization Model

## Overview
This project aims to optimize the logistics of spare parts distribution by minimizing total costs, including fixed costs for depots and transportation costs between suppliers, depots, and customers.

## Objectives
- **Cost Minimization:** Reduce overall logistics costs while meeting operational constraints.
- **Efficient Distribution:** Ensure optimal use of depots and efficient transportation routes.
- **Service Level Adherence:** Maintain service level standards to ensure timely delivery.

## Data Source
Data is sourced from CSV files containing information on transportation costs, fixed costs, demand, and weights of parts.

## Methodology
- **Data Preparation:** Load and prepare data using Pandas.
- **Model Initialization:** Set up and define the optimization model using Gurobi.
- **Variable Definition:** Establish decision variables for depot usage and shipments.
- **Objective Function:** Construct a cost-minimizing objective function.
- **Constraints:** Apply constraints for supplier weight limits, depot capacity, demand fulfillment, service levels, and inventory balance.
- **Optimization:** Update and optimize the model to find the optimal logistics configuration.
