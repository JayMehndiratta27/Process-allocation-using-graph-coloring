# Process Allocation Using Graph Coloring
This project simulates process allocation using graph coloring, a concept commonly used in compiler register allocation and resource sharing problems. It models processes and their resource conflicts as a graph, where each node is a process and edges represent conflicts between them.

Processes are allocated to a limited number of resources such that no two conflicting processes share the same resource — mimicking the graph coloring problem.

# Features
Parses process conflict graphs from standard input.

Builds an interference graph.

Uses a simplification stack (similar to Chaitin’s algorithm) for graph coloring.

Attempts resource allocation with a decreasing number of resources.

Detects resource allocation "spills" when conflicts cannot be resolved.

