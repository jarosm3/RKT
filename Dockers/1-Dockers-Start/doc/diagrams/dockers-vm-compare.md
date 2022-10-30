```mermaid
flowchart TB
    
    subgraph <b>DOCKER ENGINE</b>
        subgraph Spawn in Shared Kernel
            direction LR
            C1["Docker Container 1"]
            C2["Docker Container 2"]
            C3["Docker Container 3"]
            CV["Docker Container V"]
        end
    end

    subgraph <b>VIRTUAL BOX</b>
        subgraph Split Hardware Virtually
            direction LR
            VM1["VM 1 + Guest OS"]
            VM2["VM 2 + Guest OS"]
            VM3["VM 3 + Guest OS"]            
            VMN["VM N + Guest OS"]
        end
    end

    style CV stroke-dasharray: 5 5
    style VMN stroke-dasharray: 5 5

```