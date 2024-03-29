# Community-Detection
Detecting communities from a given undirected graph and performing a detailed analysis on the 
communities that have been detected.(Graph visualisation,Community size, Community description,Frequency plot,Radius,Degree,Center,Peripherals)

# Dataset Description
• Nodes: 351<br/>
• Edges: 1150<br/>
• Type: Undirected, Unweighted<br/>

# Tools Used
## Micro Web Framework<br/>
• Flask<br/>
## Python packages<br/>
• Networkx<br/>
Graph manipulation and visualization<br/>
• Community<br/>
This python package was used to perform community detection using the girvan-newman
algorithm <br/>
• Communities<br/>
This python package was used to perform community detection using the louvain-method 
algorithm <br/>
• Matplotlib<br/>
Used for plotting the graphs<br/>

# Step wise procedure
• Input graph is chosen of the format txt with delimiter ',' <br/>
• The graph is saved locally.<br/>
• The graph is built with the edgelist from the txt file using the networkx python package.<br/>
• Community detection algorithms are run on the graph and the graphs are coloured and saved as images in png format.<br/>
• Analysis is made and result is stored in local variables which are then passed to the html pages for display.<br/>
• Results are displayed.(Input graph, girvan-newman coloured graph, louvain coloured graph,Community size, Community description,Frequency plot,Radius,Degree,Center,Peripherals)<br/>

# Algorithms used for community detection
• Girvan - Newman<br/>
• Louvain
