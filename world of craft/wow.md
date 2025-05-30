Combat Event Prediction Using Spatial and Behavioral Data (World of Warcraft Simulation)
This project aims to predict combat events in a game-like environment based on player behavior, map positioning, and environmental factors. Inspired by the dynamics of World of Warcraft, the system analyzes player movements and surroundings to estimate whether a combat encounter is likely to occur.

Key Features
1. Spatio-Temporal Intelligence
The model leverages both spatial features (x_coord, y_coord) and temporal context (time_of_day) to detect patterns in when and where combat events are more likely to happen. This combination mirrors real-world applications in behavioral modeling and event prediction.

2. Behavior-Based Forecasting
Inputs such as player_level and num_players_nearby are used to understand player behavior and predict the probability of engagement. This allows the system to act as a smart observer of player intentions and group dynamics.

3. Class Imbalance Management
Combat events are relatively rare, so the dataset is imbalanced. To address this, class weighting is used during training, helping the model learn from limited positive samples without being biased toward the majority class.

4. Modular and Scalable Design
The architecture is flexible and can be extended with additional features such as player role (e.g., tank, healer), equipment type, or map zone. This makes the system adaptable to real game telemetry or simulation environments.

5. Simulation-Driven but Game-Ready
Although based on simulated data, the structure of this project allows for quick adaptation to real multiplayer games with available telemetry data (e.g., Dota 2, Fortnite, or WoW APIs).

6. Future Expansion Capabilities
The current model is trained using a Random Forest classifier, but the design is ready for integration with advanced models such as XGBoost, LSTM (for sequence prediction), or even Reinforcement Learning agents for real-time combat avoidance or engagement strategies.

