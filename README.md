# Indian_Railway_Analysis
This project Visualises the Indian Railways network from open data, mapping 8,100+ stations and 11,000+ trains. Nodes are stations, edges are routes, with colors for hubs, majors, clusters, and train types. The result is a stunning, galaxy-like map revealing real-world geographic and connectivity patterns.


This project uses publicly available Indian Railways data from the Open Government Data India platform, containing details of over 11,000 trains and 8,100 stations, including train numbers, names, station codes/names, arrival/departure times, distances, and source/destination stations.

The dataset is transformed into a graph network, where:
Nodes represent railway stations.
Edges represent trains traveling between stations.

Using NetworkX and force-directed layouts, the network visualization reveals:
Clusters of connectivity where frequently connected stations naturally group together.
Hub stations (red) centrally positioned due to high connectivity.
Major stations (blue), clustered small stations (orange), and trains color-coded by type (EMU – green, Express – blue, Mail – red, Others – gray).

Key insights:

The network forms visually striking clusters, resembling a cosmic map rather than a transportation grid.
Geographic relationships often align with real-world proximity (e.g., Ballia appears near Mau, Ankleshwar near Surat).
The visualization highlights the scale, complexity, and interconnectedness of the Indian Railways.
This work blends data science, network theory, and visualization to transform raw railway data into a beautiful, insight-rich graph of India’s rail network.
