# Project Overview
This is angent based model based of the This project is an Agent-Based Model (ABM) implemented using the Python-based Mesa library. The model is inspired by the seminal work "Growing Artificial Societies" by Joshua M. Epstein and Robert Axtell, which introduces the Sugar and Spice Model—a framework for exploring economic, social, and ecological dynamics in artificial societies.

# Model Overview
The Sugar and Spice Model is a conceptual ABM where agents inhabit a spatial grid with resources (sugar and spice) distributed unevenly. Each agent has individual preferences, metabolisms, and strategies for gathering, consuming, and trading resources. The overarching goal is to investigate emergent patterns of trade, wealth distribution, social networks, and resource usage.

While the original model from the book includes various extensions such as sexual reproduction, pollution, migration, and combat, this implementation focuses on the core dynamics of the sugar and spice economy with the following features:

    1. Agent Resource Collection:
        Agents gather sugar and spice from a spatially distributed resource grid.
        Each agent has a metabolism, determining how much sugar and spice it consumes at each step.

    2. Trading Mechanisms:
        Agents engage in mutually beneficial trades based on their individual resource needs and preferences.
        Trading occurs between agents in spatial proximity.

    3. Visualizing Trade Networks:
        The trade relationships form dynamic networks that are visualized in both 2D and 3D.
        These networks highlight the connections between agents and their trading partners over time.

    4. Resource Dynamics:
        Sugar and spice regenerate over time, maintaining the ecosystem's sustainability.

    5. Mesa Visualization:
        The Mesa Visualization library is used to create an interactive interface, enabling users to step through the simulation and observe changes in agent behavior, resource distributions, and network dynamics.

# Additions
This project expands on the original model by integrating additional visualization and analysis tools to enhance understanding of the emergent phenomena:

    1. Interactive 2D and 3D Network Graphs:
        Trade networks are visualized as interactive 2D and 3D graphs, using NetworkX and Matplotlib/Plotly for clear and engaging insights into agent interactions.
        Nodes represent agents, and edges represent trading relationships, with attributes like trade volume or frequency.

    2. Step-by-Step Visualization:
        The Mesa visualization interface allows users to interactively step through the model, observing real-time changes in the grid, agent states, and trade relationships.